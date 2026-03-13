# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-13 20:36:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 133378.0 (37h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 562064
telemt_connections_bad_total 15276
telemt_handshake_timeouts_total 12621
telemt_upstream_connect_attempt_total 33836
telemt_upstream_connect_success_total 33664
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 33836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5062
telemt_me_reconnect_attempts_total 31247
telemt_me_reconnect_success_total 26595
telemt_me_reader_eof_total 28386
telemt_me_idle_close_by_peer_total 28385
telemt_me_route_drop_no_conn_total 185851
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 484461
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1548
telemt_desync_full_logged_total 525
telemt_desync_suppressed_total 1023
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 571
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 27039
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26579
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 444
telemt_user_connections_total{user="hello"} 484356
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 11462000306 (10.67 GB)
telemt_user_octets_to_client{user="hello"} 234076078036 (218.00 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 133271.5 (37h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284150
telemt_connections_bad_total 2101
telemt_handshake_timeouts_total 1895
telemt_upstream_connect_attempt_total 134362
telemt_upstream_connect_success_total 133386
telemt_upstream_connect_fail_total 975
telemt_upstream_connect_attempts_per_request{bucket="1"} 134361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28854
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2377
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 975
telemt_me_keepalive_timeout_total 3649
telemt_me_reconnect_attempts_total 140792
telemt_me_reconnect_success_total 26440
telemt_me_reader_eof_total 30745
telemt_me_idle_close_by_peer_total 30745
telemt_me_route_drop_no_conn_total 84029
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169416
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 30258
telemt_me_refill_failed_total 3568
telemt_me_writer_restored_same_endpoint_total 26423
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3818
telemt_user_connections_total{user="hello"} 269502
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 2809226953 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 81814146825 (76.20 GB)
telemt_user_msgs_from_client{user="hello"} 1635320
telemt_user_msgs_to_client{user="hello"} 9056914
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 133235.2 (37h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330556
telemt_connections_bad_total 2644
telemt_handshake_timeouts_total 24362
telemt_upstream_connect_attempt_total 35390
telemt_upstream_connect_success_total 35385
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 35390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2818
telemt_me_reconnect_attempts_total 29944
telemt_me_reconnect_success_total 28705
telemt_me_reader_eof_total 30776
telemt_me_idle_close_by_peer_total 30776
telemt_me_route_drop_no_conn_total 118366
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291960
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 29029
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 28685
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 291873
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 11886009964 (11.07 GB)
telemt_user_octets_to_client{user="hello"} 122000322108 (113.62 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 133211.0 (37h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436678
telemt_connections_bad_total 15238
telemt_handshake_timeouts_total 4183
telemt_upstream_connect_attempt_total 63416
telemt_upstream_connect_success_total 53102
telemt_upstream_connect_fail_total 10314
telemt_upstream_connect_attempts_per_request{bucket="1"} 63416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19655
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 299
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10314
telemt_me_keepalive_timeout_total 4763
telemt_me_reconnect_attempts_total 121876
telemt_me_reconnect_success_total 27442
telemt_me_reader_eof_total 31169
telemt_me_idle_close_by_peer_total 31162
telemt_me_route_drop_no_conn_total 151645
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367607
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1513
telemt_desync_full_logged_total 449
telemt_desync_suppressed_total 1064
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 578
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 30740
telemt_me_refill_failed_total 2945
telemt_me_writer_restored_same_endpoint_total 27432
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3298
telemt_user_connections_total{user="hello"} 386464
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 8719959667 (8.12 GB)
telemt_user_octets_to_client{user="hello"} 142630621992 (132.84 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 83382.2 (23h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142711
telemt_connections_bad_total 19518
telemt_handshake_timeouts_total 1445
telemt_upstream_connect_attempt_total 31621
telemt_upstream_connect_success_total 31317
telemt_upstream_connect_fail_total 304
telemt_upstream_connect_attempts_per_request{bucket="1"} 31621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 304
telemt_me_keepalive_timeout_total 1281
telemt_me_reconnect_attempts_total 35650
telemt_me_reconnect_success_total 22257
telemt_me_reader_eof_total 23843
telemt_me_idle_close_by_peer_total 23843
telemt_me_route_drop_no_conn_total 44134
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112336
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 607
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 22884
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22239
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 117230
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 1368297169 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 53012216667 (49.37 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 133166.8 (36h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814142
telemt_connections_bad_total 25016
telemt_handshake_timeouts_total 25005
telemt_upstream_connect_attempt_total 27443
telemt_upstream_connect_success_total 27298
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 27443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14502
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 3094
telemt_me_reconnect_attempts_total 25357
telemt_me_reconnect_success_total 20708
telemt_me_reader_eof_total 22206
telemt_me_idle_close_by_peer_total 22203
telemt_me_route_drop_no_conn_total 387869
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 763430
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 21128
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20701
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 420
telemt_user_connections_total{user="hello"} 736293
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 12906285588 (12.02 GB)
telemt_user_octets_to_client{user="hello"} 364055126372 (339.05 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 47
```
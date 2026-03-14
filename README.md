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

# Server Metrics 2026-03-14 03:39:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 158737.4 (44h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618818
telemt_connections_bad_total 30492
telemt_handshake_timeouts_total 12932
telemt_upstream_connect_attempt_total 40608
telemt_upstream_connect_success_total 40404
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 40607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5543
telemt_me_reconnect_attempts_total 36775
telemt_me_reconnect_success_total 32093
telemt_me_reader_eof_total 34297
telemt_me_idle_close_by_peer_total 34296
telemt_me_route_drop_no_conn_total 200990
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 523999
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1782
telemt_desync_full_logged_total 603
telemt_desync_suppressed_total 1179
telemt_desync_frames_bucket_total{bucket="1_2"} 376
telemt_desync_frames_bucket_total{bucket="3_10"} 664
telemt_desync_frames_bucket_total{bucket="gt_10"} 742
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 32591
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 32073
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 523890
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 15699520146 (14.62 GB)
telemt_user_octets_to_client{user="hello"} 256300905688 (238.70 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 158630.4 (44h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312944
telemt_connections_bad_total 2265
telemt_handshake_timeouts_total 1945
telemt_upstream_connect_attempt_total 146069
telemt_upstream_connect_success_total 144903
telemt_upstream_connect_fail_total 1166
telemt_upstream_connect_attempts_per_request{bucket="1"} 146069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1166
telemt_me_keepalive_timeout_total 3847
telemt_me_reconnect_attempts_total 166669
telemt_me_reconnect_success_total 33669
telemt_me_reader_eof_total 38713
telemt_me_idle_close_by_peer_total 38713
telemt_me_route_drop_no_conn_total 98853
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193647
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 38144
telemt_me_refill_failed_total 4150
telemt_me_writer_restored_same_endpoint_total 33652
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4475
telemt_user_connections_total{user="hello"} 296759
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 3105057775 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 95357301215 (88.81 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 158597.7 (44h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366016
telemt_connections_bad_total 2910
telemt_handshake_timeouts_total 34785
telemt_upstream_connect_attempt_total 42069
telemt_upstream_connect_success_total 42063
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 42069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3319
telemt_me_reconnect_attempts_total 35375
telemt_me_reconnect_success_total 34101
telemt_me_reader_eof_total 36651
telemt_me_idle_close_by_peer_total 36651
telemt_me_route_drop_no_conn_total 130563
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315637
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
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
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 34501
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 34080
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 315455
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 12644458240 (11.78 GB)
telemt_user_octets_to_client{user="hello"} 127643039464 (118.88 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 158569.5 (44h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467471
telemt_connections_bad_total 15544
telemt_handshake_timeouts_total 4398
telemt_upstream_connect_attempt_total 71753
telemt_upstream_connect_success_total 61254
telemt_upstream_connect_fail_total 10499
telemt_upstream_connect_attempts_per_request{bucket="1"} 71753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24269
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10499
telemt_me_keepalive_timeout_total 5137
telemt_me_reconnect_attempts_total 140344
telemt_me_reconnect_success_total 34299
telemt_me_reader_eof_total 38635
telemt_me_idle_close_by_peer_total 38627
telemt_me_route_drop_no_conn_total 166143
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396480
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 38007
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 34289
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3708
telemt_user_connections_total{user="hello"} 415310
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 9117148531 (8.49 GB)
telemt_user_octets_to_client{user="hello"} 161450861604 (150.36 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 108741.1 (30h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180493
telemt_connections_bad_total 26040
telemt_handshake_timeouts_total 1577
telemt_upstream_connect_attempt_total 39399
telemt_upstream_connect_success_total 39034
telemt_upstream_connect_fail_total 365
telemt_upstream_connect_attempts_per_request{bucket="1"} 39399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 365
telemt_me_keepalive_timeout_total 2364
telemt_me_reconnect_attempts_total 42156
telemt_me_reconnect_success_total 28736
telemt_me_reader_eof_total 30735
telemt_me_idle_close_by_peer_total 30735
telemt_me_route_drop_no_conn_total 53469
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143000
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 29414
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 28718
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 678
telemt_user_connections_total{user="hello"} 147760
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 2198537809 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 68679241451 (63.96 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 158525.6 (44h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 905008
telemt_connections_bad_total 28076
telemt_handshake_timeouts_total 25412
telemt_upstream_connect_attempt_total 32957
telemt_upstream_connect_success_total 32783
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 32957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 3506
telemt_me_reconnect_attempts_total 29585
telemt_me_reconnect_success_total 24917
telemt_me_reader_eof_total 26704
telemt_me_idle_close_by_peer_total 26701
telemt_me_route_drop_no_conn_total 431209
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 846354
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 758
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 25381
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24910
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 819019
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 14352030780 (13.37 GB)
telemt_user_octets_to_client{user="hello"} 413257365412 (384.88 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 39
```
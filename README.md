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

# Server Metrics 2026-03-14 18:25:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 18560.1 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105519
telemt_connections_bad_total 15478
telemt_handshake_timeouts_total 761
telemt_upstream_connect_attempt_total 4382
telemt_upstream_connect_success_total 4380
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 3437
telemt_me_reconnect_success_total 3405
telemt_me_reader_eof_total 3599
telemt_me_idle_close_by_peer_total 3599
telemt_me_route_drop_no_conn_total 37014
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84921
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3459
telemt_me_writer_restored_same_endpoint_total 3387
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 84849
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 1750754140 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 42987818392 (40.04 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 18558.5 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42240
telemt_connections_bad_total 501
telemt_handshake_timeouts_total 852
telemt_upstream_connect_attempt_total 5011
telemt_upstream_connect_success_total 4975
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 5011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2876
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 6574
telemt_me_reconnect_success_total 4000
telemt_me_reader_eof_total 4245
telemt_me_idle_close_by_peer_total 4245
telemt_me_route_drop_no_conn_total 22546
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39356
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 4138
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 3995
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 39340
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 572999856 (546.46 MB)
telemt_user_octets_to_client{user="hello"} 16958783732 (15.79 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 18562.7 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45277
telemt_connections_bad_total 369
telemt_handshake_timeouts_total 1766
telemt_upstream_connect_attempt_total 6775
telemt_upstream_connect_success_total 6704
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 6775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 103270
telemt_me_reconnect_success_total 5410
telemt_me_reader_eof_total 5771
telemt_me_idle_close_by_peer_total 5771
telemt_me_route_drop_no_conn_total 17877
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40643
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5673
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5372
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 40711
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 2908054533 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 23779984390 (22.15 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 18567.7 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57331
telemt_connections_bad_total 132
telemt_handshake_timeouts_total 463
telemt_upstream_connect_attempt_total 4641
telemt_upstream_connect_success_total 4613
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 3668
telemt_me_reconnect_success_total 3647
telemt_me_reader_eof_total 3815
telemt_me_idle_close_by_peer_total 3815
telemt_me_route_drop_no_conn_total 25862
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54283
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 453
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3687
telemt_me_writer_restored_same_endpoint_total 3645
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 54161
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 740643544 (706.33 MB)
telemt_user_octets_to_client{user="hello"} 17332405540 (16.14 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 18560.7 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43097
telemt_connections_bad_total 3598
telemt_handshake_timeouts_total 2521
telemt_upstream_connect_attempt_total 4275
telemt_upstream_connect_success_total 4229
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 4275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 9779
telemt_me_reconnect_success_total 3254
telemt_me_reader_eof_total 3571
telemt_me_idle_close_by_peer_total 3571
telemt_me_route_drop_no_conn_total 14702
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34820
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3488
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3250
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 34812
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 565564776 (539.36 MB)
telemt_user_octets_to_client{user="hello"} 9576585680 (8.92 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 18560.4 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149476
telemt_connections_bad_total 7173
telemt_handshake_timeouts_total 1996
telemt_upstream_connect_attempt_total 3764
telemt_upstream_connect_success_total 3695
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 3764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1871
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 7718
telemt_me_reconnect_success_total 2719
telemt_me_reader_eof_total 2962
telemt_me_idle_close_by_peer_total 2962
telemt_me_route_drop_no_conn_total 80217
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134935
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2903
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2715
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 132597
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 3106267028 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 69105047036 (64.36 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 70
```
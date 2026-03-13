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

# Server Metrics 2026-03-13 01:19:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 63988.2 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262489
telemt_connections_bad_total 2766
telemt_handshake_timeouts_total 5598
telemt_upstream_connect_attempt_total 16175
telemt_upstream_connect_success_total 16104
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 16175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8939
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1506
telemt_me_reconnect_attempts_total 16334
telemt_me_reconnect_success_total 12859
telemt_me_reader_eof_total 13713
telemt_me_idle_close_by_peer_total 13712
telemt_me_route_drop_no_conn_total 81825
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217438
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 728
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 328
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13107
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 12843
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 217206
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 3931115720 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 109286194404 (101.78 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 63881.3 (17h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121938
telemt_connections_bad_total 733
telemt_handshake_timeouts_total 974
telemt_upstream_connect_attempt_total 35839
telemt_upstream_connect_success_total 35409
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 35839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_keepalive_timeout_total 457
telemt_me_reconnect_attempts_total 59930
telemt_me_reconnect_success_total 15719
telemt_me_reader_eof_total 17522
telemt_me_idle_close_by_peer_total 17522
telemt_me_route_drop_no_conn_total 43423
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99234
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 17214
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 15704
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1495
telemt_user_connections_total{user="hello"} 115734
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 1243335056 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 35019399251 (32.61 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 63845.0 (17h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147345
telemt_connections_bad_total 1687
telemt_handshake_timeouts_total 2333
telemt_upstream_connect_attempt_total 17602
telemt_upstream_connect_success_total 17600
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 17602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9384
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 367
telemt_me_reconnect_attempts_total 15524
telemt_me_reconnect_success_total 14368
telemt_me_reader_eof_total 15349
telemt_me_idle_close_by_peer_total 15349
telemt_me_route_drop_no_conn_total 55927
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137799
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14530
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 14348
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 137763
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 2634153656 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 62886827164 (58.57 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 63820.4 (17h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210618
telemt_connections_bad_total 13301
telemt_handshake_timeouts_total 1426
telemt_upstream_connect_attempt_total 29623
telemt_upstream_connect_success_total 19859
telemt_upstream_connect_fail_total 9764
telemt_upstream_connect_attempts_per_request{bucket="1"} 29623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9764
telemt_me_keepalive_timeout_total 3214
telemt_me_reconnect_attempts_total 50701
telemt_me_reconnect_success_total 13804
telemt_me_reader_eof_total 15441
telemt_me_idle_close_by_peer_total 15434
telemt_me_route_drop_no_conn_total 75820
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174377
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 15162
telemt_me_refill_failed_total 1149
telemt_me_writer_restored_same_endpoint_total 13794
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1358
telemt_user_connections_total{user="hello"} 177129
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 3023257922 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 72748484853 (67.75 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13992.0 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12550
telemt_connections_bad_total 2655
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 4379
telemt_upstream_connect_success_total 4340
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 4379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 3627
telemt_me_reconnect_success_total 3618
telemt_me_reader_eof_total 3860
telemt_me_idle_close_by_peer_total 3860
telemt_me_route_drop_no_conn_total 3895
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9486
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3638
telemt_me_writer_restored_same_endpoint_total 3602
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 9486
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 37417196 (35.68 MB)
telemt_user_octets_to_client{user="hello"} 2811207300 (2.62 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 63777.0 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353813
telemt_connections_bad_total 6544
telemt_handshake_timeouts_total 2603
telemt_upstream_connect_attempt_total 13500
telemt_upstream_connect_success_total 13428
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 13500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 1339
telemt_me_reconnect_attempts_total 13874
telemt_me_reconnect_success_total 10256
telemt_me_reader_eof_total 11001
telemt_me_idle_close_by_peer_total 10999
telemt_me_route_drop_no_conn_total 158058
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 346156
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10494
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 10249
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 334457
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 5682026632 (5.29 GB)
telemt_user_octets_to_client{user="hello"} 180908258176 (168.48 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 23
```
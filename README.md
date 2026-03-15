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

# Server Metrics 2026-03-15 20:30:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 80143.3 (22h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376721
telemt_connections_bad_total 4910
telemt_handshake_timeouts_total 13685
telemt_upstream_connect_attempt_total 19166
telemt_upstream_connect_success_total 19071
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 19166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10583
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 18486
telemt_me_reconnect_success_total 15083
telemt_me_reader_eof_total 16081
telemt_me_idle_close_by_peer_total 16081
telemt_me_route_drop_no_conn_total 478540
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 404796
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1985
telemt_desync_full_logged_total 776
telemt_desync_suppressed_total 1209
telemt_desync_frames_bucket_total{bucket="1_2"} 374
telemt_desync_frames_bucket_total{bucket="3_10"} 774
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 15356
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 15049
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 273
telemt_user_connections_total{user="hello"} 343856
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 7742961364 (7.21 GB)
telemt_user_octets_to_client{user="hello"} 262602204564 (244.57 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 80150.7 (22h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155073
telemt_connections_bad_total 2860
telemt_handshake_timeouts_total 13457
telemt_upstream_connect_attempt_total 22049
telemt_upstream_connect_success_total 21985
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 22049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 578
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 1217
telemt_me_reconnect_attempts_total 20594
telemt_me_reconnect_success_total 17599
telemt_me_reader_eof_total 18737
telemt_me_idle_close_by_peer_total 18736
telemt_me_route_drop_no_conn_total 64331
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132250
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 17962
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 17583
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 363
telemt_user_connections_total{user="hello"} 132522
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 2445001753 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 67177679948 (62.56 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 80143.6 (22h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154643
telemt_connections_bad_total 1730
telemt_handshake_timeouts_total 3392
telemt_upstream_connect_attempt_total 22992
telemt_upstream_connect_success_total 22984
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 22992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 26306
telemt_me_reconnect_success_total 18940
telemt_me_reader_eof_total 20338
telemt_me_idle_close_by_peer_total 20337
telemt_me_route_drop_no_conn_total 61284
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137171
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 19357
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 18932
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 417
telemt_user_connections_total{user="hello"} 137058
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 10909128180 (10.16 GB)
telemt_user_octets_to_client{user="hello"} 78915906172 (73.50 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 80143.1 (22h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223071
telemt_connections_bad_total 1178
telemt_handshake_timeouts_total 1575
telemt_upstream_connect_attempt_total 18734
telemt_upstream_connect_success_total 18718
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 18734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9669
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 14825
telemt_me_reconnect_success_total 14735
telemt_me_reader_eof_total 15692
telemt_me_idle_close_by_peer_total 15692
telemt_me_route_drop_no_conn_total 81838
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205293
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 779
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 505
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 14911
telemt_me_writer_restored_same_endpoint_total 14724
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 205211
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 3822978136 (3.56 GB)
telemt_user_octets_to_client{user="hello"} 93046184080 (86.66 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 55214.4 (15h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134413
telemt_connections_bad_total 26376
telemt_handshake_timeouts_total 2512
telemt_upstream_connect_attempt_total 16157
telemt_upstream_connect_success_total 16058
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 16157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 107565
telemt_me_reconnect_success_total 13113
telemt_me_reader_eof_total 13804
telemt_me_idle_close_by_peer_total 13804
telemt_me_route_drop_no_conn_total 45277
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101841
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 319
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 249
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 150
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 13201
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 13009
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 101970
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 1613300889 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 39365128587 (36.66 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 80142.8 (22h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 544353
telemt_connections_bad_total 58457
telemt_handshake_timeouts_total 4319
telemt_upstream_connect_attempt_total 17012
telemt_upstream_connect_success_total 16916
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 17012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 14214
telemt_me_reconnect_success_total 12904
telemt_me_reader_eof_total 13712
telemt_me_idle_close_by_peer_total 13712
telemt_me_route_drop_no_conn_total 403463
telemt_me_route_drop_channel_closed_total 94
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 538260
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 323
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 13083
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 12877
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 461209
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 11700264396 (10.90 GB)
telemt_user_octets_to_client{user="hello"} 267920418944 (249.52 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 73
```
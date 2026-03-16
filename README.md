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

# Server Metrics 2026-03-16 12:55:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 139275.9 (38h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 782712
telemt_connections_bad_total 54226
telemt_handshake_timeouts_total 25116
telemt_upstream_connect_attempt_total 32145
telemt_upstream_connect_success_total 31989
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 32145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 39306
telemt_me_reconnect_success_total 25071
telemt_me_reader_eof_total 27036
telemt_me_idle_close_by_peer_total 27036
telemt_me_route_drop_no_conn_total 615123
telemt_me_route_drop_channel_closed_total 98
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 718023
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3418
telemt_desync_full_logged_total 1283
telemt_desync_suppressed_total 2135
telemt_desync_frames_bucket_total{bucket="1_2"} 720
telemt_desync_frames_bucket_total{bucket="3_10"} 1429
telemt_desync_frames_bucket_total{bucket="gt_10"} 1269
telemt_pool_swap_total 125
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25789
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 25036
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 654498
telemt_user_connections_current{user="hello"} 734
telemt_user_octets_from_client{user="hello"} 13662768768 (12.72 GB)
telemt_user_octets_to_client{user="hello"} 375924878896 (350.11 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 139284.5 (38h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328116
telemt_connections_bad_total 4713
telemt_handshake_timeouts_total 21039
telemt_upstream_connect_attempt_total 37227
telemt_upstream_connect_success_total 37120
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 37227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 875
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 43514
telemt_me_reconnect_success_total 29567
telemt_me_reader_eof_total 31742
telemt_me_idle_close_by_peer_total 31741
telemt_me_route_drop_no_conn_total 154689
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290354
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 238
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 30426
telemt_me_refill_failed_total 426
telemt_me_writer_restored_same_endpoint_total 29551
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 859
telemt_user_connections_total{user="hello"} 290034
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 5817833217 (5.42 GB)
telemt_user_octets_to_client{user="hello"} 141425087080 (131.71 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 139275.8 (38h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313808
telemt_connections_bad_total 6693
telemt_handshake_timeouts_total 9004
telemt_upstream_connect_attempt_total 38412
telemt_upstream_connect_success_total 38404
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 38412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 38853
telemt_me_reconnect_success_total 31405
telemt_me_reader_eof_total 33712
telemt_me_idle_close_by_peer_total 33711
telemt_me_route_drop_no_conn_total 106636
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256601
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 31960
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 31397
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 256196
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 19019690089 (17.71 GB)
telemt_user_octets_to_client{user="hello"} 132457304416 (123.36 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 139275.4 (38h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481290
telemt_connections_bad_total 5598
telemt_handshake_timeouts_total 6098
telemt_upstream_connect_attempt_total 32320
telemt_upstream_connect_success_total 32272
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 32319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 30342
telemt_me_reconnect_success_total 25331
telemt_me_reader_eof_total 27100
telemt_me_idle_close_by_peer_total 27099
telemt_me_route_drop_no_conn_total 160616
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 439899
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1569
telemt_desync_full_logged_total 527
telemt_desync_suppressed_total 1042
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 678
telemt_desync_frames_bucket_total{bucket="gt_10"} 577
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 25827
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 25320
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 439723
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 6710045974 (6.25 GB)
telemt_user_octets_to_client{user="hello"} 166041234784 (154.64 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 114346.8 (31h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297960
telemt_connections_bad_total 54945
telemt_handshake_timeouts_total 5237
telemt_upstream_connect_attempt_total 32443
telemt_upstream_connect_success_total 32264
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 32443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 122027
telemt_me_reconnect_success_total 26409
telemt_me_reader_eof_total 28049
telemt_me_idle_close_by_peer_total 28049
telemt_me_route_drop_no_conn_total 88573
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228680
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 720
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 546
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 26682
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 26305
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 273
telemt_user_connections_total{user="hello"} 228282
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 2948903713 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 104981670559 (97.77 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 139274.8 (38h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1013167
telemt_connections_bad_total 78073
telemt_handshake_timeouts_total 12919
telemt_upstream_connect_attempt_total 29493
telemt_upstream_connect_success_total 29339
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 29493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 26032
telemt_me_reconnect_success_total 22380
telemt_me_reader_eof_total 23901
telemt_me_idle_close_by_peer_total 23900
telemt_me_route_drop_no_conn_total 721346
telemt_me_route_drop_channel_closed_total 138
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 983078
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 709
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 22768
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 22353
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 841659
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 17910680840 (16.68 GB)
telemt_user_octets_to_client{user="hello"} 482604678696 (449.46 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 112
```
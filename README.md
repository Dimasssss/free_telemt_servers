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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 09:07:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 51725.5 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393483
telemt_connections_bad_total 3633
telemt_handshake_timeouts_total 11810
telemt_upstream_connect_attempt_total 13325
telemt_upstream_connect_success_total 12895
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 13325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 9546
telemt_me_reconnect_success_total 8025
telemt_me_reader_eof_total 8529
telemt_me_idle_close_by_peer_total 8528
telemt_me_route_drop_no_conn_total 123778
telemt_me_route_drop_channel_closed_total 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 354231
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2725
telemt_desync_full_logged_total 761
telemt_desync_suppressed_total 1964
telemt_desync_frames_bucket_total{bucket="1_2"} 631
telemt_desync_frames_bucket_total{bucket="3_10"} 1265
telemt_desync_frames_bucket_total{bucket="gt_10"} 829
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8189
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8003
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 356226
telemt_user_connections_current{user="hello"} 895
telemt_user_octets_from_client{user="hello"} 4924280191 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 141260955155 (131.56 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 51977.4 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213835
telemt_connections_bad_total 2374
telemt_handshake_timeouts_total 12438
telemt_upstream_connect_attempt_total 13916
telemt_upstream_connect_success_total 13731
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 13916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7712
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 15807
telemt_me_reconnect_success_total 11164
telemt_me_reader_eof_total 11870
telemt_me_idle_close_by_peer_total 11870
telemt_me_route_drop_no_conn_total 77918
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188504
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 506
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 322
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11421
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 11148
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 188510
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 2243500068 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 75330365300 (70.16 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 51753.7 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131627
telemt_connections_bad_total 7571
telemt_handshake_timeouts_total 8231
telemt_upstream_connect_attempt_total 13730
telemt_upstream_connect_success_total 13659
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7560
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 12013
telemt_me_reconnect_success_total 11047
telemt_me_reader_eof_total 11815
telemt_me_idle_close_by_peer_total 11815
telemt_me_route_drop_no_conn_total 40326
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106665
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 217
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11219
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 11036
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 106590
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 7204159312 (6.71 GB)
telemt_user_octets_to_client{user="hello"} 33838419200 (31.51 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 51812.7 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286701
telemt_connections_bad_total 6179
telemt_handshake_timeouts_total 10653
telemt_upstream_connect_attempt_total 11842
telemt_upstream_connect_success_total 11735
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 11842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6119
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 10166
telemt_me_reconnect_success_total 9088
telemt_me_reader_eof_total 9673
telemt_me_idle_close_by_peer_total 9673
telemt_me_route_drop_no_conn_total 78959
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227604
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 472
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 294
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9262
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9080
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 227562
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 2397632722 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 94417053385 (87.93 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 51784.7 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162241
telemt_connections_bad_total 43887
telemt_handshake_timeouts_total 2726
telemt_upstream_connect_attempt_total 15803
telemt_upstream_connect_success_total 15594
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 15803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_reconnect_attempts_total 20002
telemt_me_reconnect_success_total 12893
telemt_me_reader_eof_total 13677
telemt_me_idle_close_by_peer_total 13677
telemt_me_route_drop_no_conn_total 42557
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110630
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 330
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 13275
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 12885
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 110658
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 1743011655 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 50539816094 (47.07 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 51946.0 (14h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386703
telemt_connections_bad_total 46767
telemt_handshake_timeouts_total 3870
telemt_upstream_connect_attempt_total 10661
telemt_upstream_connect_success_total 10603
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 10661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11902
telemt_me_reconnect_success_total 8024
telemt_me_reader_eof_total 8669
telemt_me_idle_close_by_peer_total 8669
telemt_me_route_drop_no_conn_total 263575
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392375
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 507
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8264
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8010
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 314271
telemt_user_connections_current{user="hello"} 938
telemt_user_octets_from_client{user="hello"} 4564659216 (4.25 GB)
telemt_user_octets_to_client{user="hello"} 178467416676 (166.21 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 39952.2 (11h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4518
telemt_connections_bad_total 234
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 19527
telemt_upstream_connect_success_total 19513
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 19527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 17540
telemt_me_reconnect_success_total 17411
telemt_me_reader_eof_total 18981
telemt_me_idle_close_by_peer_total 18981
telemt_me_route_drop_no_conn_total 942
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4209
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 17571
telemt_me_writer_restored_same_endpoint_total 17411
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 4209
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 733792384 (699.80 MB)
telemt_user_octets_to_client{user="hello"} 22467086816 (20.92 GB)
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 9
```
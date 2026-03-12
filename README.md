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

# Server Metrics 2026-03-12 17:50:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 37013.7 (10h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191926
telemt_connections_bad_total 2414
telemt_handshake_timeouts_total 4938
telemt_upstream_connect_attempt_total 9432
telemt_upstream_connect_success_total 9389
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 9432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1370
telemt_me_reconnect_attempts_total 10913
telemt_me_reconnect_success_total 7461
telemt_me_reader_eof_total 7900
telemt_me_idle_close_by_peer_total 7899
telemt_me_route_drop_no_conn_total 56943
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162447
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 630
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 393
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 7653
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 7445
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 162407
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 2900626516 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 69575573096 (64.80 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 36906.2 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81309
telemt_connections_bad_total 469
telemt_handshake_timeouts_total 658
telemt_upstream_connect_attempt_total 12955
telemt_upstream_connect_success_total 12711
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 12955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 319
telemt_me_reconnect_attempts_total 37406
telemt_me_reconnect_success_total 8986
telemt_me_reader_eof_total 10047
telemt_me_idle_close_by_peer_total 10047
telemt_me_route_drop_no_conn_total 35061
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75399
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 9946
telemt_me_refill_failed_total 887
telemt_me_writer_restored_same_endpoint_total 8971
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 960
telemt_user_connections_total{user="hello"} 77255
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 837549665 (798.75 MB)
telemt_user_octets_to_client{user="hello"} 21220777104 (19.76 GB)
telemt_user_msgs_from_client{user="hello"} 28126
telemt_user_msgs_to_client{user="hello"} 198403
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 36869.9 (10h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108722
telemt_connections_bad_total 1507
telemt_handshake_timeouts_total 2094
telemt_upstream_connect_attempt_total 10096
telemt_upstream_connect_success_total 10096
telemt_upstream_connect_attempts_per_request{bucket="1"} 10096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5217
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 229
telemt_me_reconnect_attempts_total 8263
telemt_me_reconnect_success_total 8191
telemt_me_reader_eof_total 8681
telemt_me_idle_close_by_peer_total 8681
telemt_me_route_drop_no_conn_total 40635
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100645
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8268
telemt_me_writer_restored_same_endpoint_total 8171
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 100617
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 2355077160 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 52673242924 (49.06 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 36845.6 (10h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148610
telemt_connections_bad_total 13088
telemt_handshake_timeouts_total 1105
telemt_upstream_connect_attempt_total 8251
telemt_upstream_connect_success_total 7993
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 8251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_keepalive_timeout_total 371
telemt_me_reconnect_attempts_total 34220
telemt_me_reconnect_success_total 6128
telemt_me_reader_eof_total 7145
telemt_me_idle_close_by_peer_total 7145
telemt_me_route_drop_no_conn_total 53990
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127076
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 432
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 7074
telemt_me_refill_failed_total 876
telemt_me_writer_restored_same_endpoint_total 6120
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 946
telemt_user_connections_total{user="hello"} 126958
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 2245929128 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 52507883944 (48.90 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 36814.8 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91787
telemt_connections_bad_total 9597
telemt_handshake_timeouts_total 1165
telemt_upstream_connect_attempt_total 49114
telemt_upstream_connect_success_total 48670
telemt_upstream_connect_fail_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 49114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 444
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 50632
telemt_me_reconnect_success_total 3731
telemt_me_reader_eof_total 5194
telemt_me_idle_close_by_peer_total 5194
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 13380
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35378
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 5222
telemt_me_refill_failed_total 1468
telemt_me_writer_restored_same_endpoint_total 3714
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1491
telemt_user_connections_total{user="hello"} 78455
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 713323038 (680.28 MB)
telemt_user_octets_to_client{user="hello"} 23047176648 (21.46 GB)
telemt_user_msgs_from_client{user="hello"} 670802
telemt_user_msgs_to_client{user="hello"} 2534058
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 36802.7 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234969
telemt_connections_bad_total 1223
telemt_handshake_timeouts_total 2009
telemt_upstream_connect_attempt_total 7859
telemt_upstream_connect_success_total 7821
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 7859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 446
telemt_me_reconnect_attempts_total 9560
telemt_me_reconnect_success_total 5959
telemt_me_reader_eof_total 6349
telemt_me_idle_close_by_peer_total 6348
telemt_me_route_drop_no_conn_total 107752
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234187
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6149
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 5952
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 224121
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 3986952604 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 103928870676 (96.79 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 64
```
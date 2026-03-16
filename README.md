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

# Server Metrics 2026-03-16 03:08:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 104027.0 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 447019
telemt_connections_bad_total 5370
telemt_handshake_timeouts_total 15088
telemt_upstream_connect_attempt_total 24881
telemt_upstream_connect_success_total 24766
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 24881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 23030
telemt_me_reconnect_success_total 19608
telemt_me_reader_eof_total 20967
telemt_me_idle_close_by_peer_total 20967
telemt_me_route_drop_no_conn_total 499761
telemt_me_route_drop_channel_closed_total 79
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470502
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2290
telemt_desync_full_logged_total 919
telemt_desync_suppressed_total 1371
telemt_desync_frames_bucket_total{bucket="1_2"} 458
telemt_desync_frames_bucket_total{bucket="3_10"} 897
telemt_desync_frames_bucket_total{bucket="gt_10"} 935
telemt_pool_swap_total 99
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19927
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 19574
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 409356
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 8471611732 (7.89 GB)
telemt_user_octets_to_client{user="hello"} 291693975900 (271.66 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 104033.1 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181926
telemt_connections_bad_total 2968
telemt_handshake_timeouts_total 14621
telemt_upstream_connect_attempt_total 28378
telemt_upstream_connect_success_total 28303
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 28378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 29638
telemt_me_reconnect_success_total 22732
telemt_me_reader_eof_total 24350
telemt_me_idle_close_by_peer_total 24349
telemt_me_route_drop_no_conn_total 92142
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157734
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 23267
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 22716
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 535
telemt_user_connections_total{user="hello"} 157280
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 3459037553 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 81226056844 (75.65 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 104025.8 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199244
telemt_connections_bad_total 2862
telemt_handshake_timeouts_total 3897
telemt_upstream_connect_attempt_total 29468
telemt_upstream_connect_success_total 29460
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 29468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 31628
telemt_me_reconnect_success_total 24241
telemt_me_reader_eof_total 26103
telemt_me_idle_close_by_peer_total 26102
telemt_me_route_drop_no_conn_total 71188
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160330
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
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 24709
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 24233
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 160062
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 16419511945 (15.29 GB)
telemt_user_octets_to_client{user="hello"} 101290123016 (94.33 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 104025.5 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265141
telemt_connections_bad_total 1222
telemt_handshake_timeouts_total 1687
telemt_upstream_connect_attempt_total 24400
telemt_upstream_connect_success_total 24379
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 24400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 19333
telemt_me_reconnect_success_total 19219
telemt_me_reader_eof_total 20513
telemt_me_idle_close_by_peer_total 20512
telemt_me_route_drop_no_conn_total 97069
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245080
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 881
telemt_desync_full_logged_total 312
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 381
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 19452
telemt_me_writer_restored_same_endpoint_total 19208
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 244962
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 4219279244 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 111320539972 (103.68 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 79096.9 (21h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175373
telemt_connections_bad_total 31079
telemt_handshake_timeouts_total 3074
telemt_upstream_connect_attempt_total 22562
telemt_upstream_connect_success_total 22438
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 22562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 112823
telemt_me_reconnect_success_total 18353
telemt_me_reader_eof_total 19472
telemt_me_idle_close_by_peer_total 19472
telemt_me_route_drop_no_conn_total 54885
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136539
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 18496
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 18249
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 136566
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 1918682485 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 53696388335 (50.01 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 104024.6 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672653
telemt_connections_bad_total 58739
telemt_handshake_timeouts_total 5020
telemt_upstream_connect_attempt_total 22096
telemt_upstream_connect_success_total 21978
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 22096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 18122
telemt_me_reconnect_success_total 16790
telemt_me_reader_eof_total 17917
telemt_me_idle_close_by_peer_total 17917
telemt_me_route_drop_no_conn_total 592616
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 698083
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 17026
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 16763
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 556761
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 12963419692 (12.07 GB)
telemt_user_octets_to_client{user="hello"} 342037993204 (318.55 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 37
```
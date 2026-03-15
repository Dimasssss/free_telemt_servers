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

# Server Metrics 2026-03-15 18:32:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 73100.3 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343363
telemt_connections_bad_total 4198
telemt_handshake_timeouts_total 11221
telemt_upstream_connect_attempt_total 17703
telemt_upstream_connect_success_total 17615
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 17703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9765
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17348
telemt_me_reconnect_success_total 13949
telemt_me_reader_eof_total 14863
telemt_me_idle_close_by_peer_total 14863
telemt_me_route_drop_no_conn_total 465199
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375749
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1890
telemt_desync_full_logged_total 748
telemt_desync_suppressed_total 1142
telemt_desync_frames_bucket_total{bucket="1_2"} 358
telemt_desync_frames_bucket_total{bucket="3_10"} 735
telemt_desync_frames_bucket_total{bucket="gt_10"} 797
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 14206
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13915
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 314849
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 6423097884 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 244731970372 (227.92 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 73107.1 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137816
telemt_connections_bad_total 2839
telemt_handshake_timeouts_total 12456
telemt_upstream_connect_attempt_total 19766
telemt_upstream_connect_success_total 19766
telemt_upstream_connect_attempts_per_request{bucket="1"} 19766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 18426
telemt_me_reconnect_success_total 16059
telemt_me_reader_eof_total 17175
telemt_me_idle_close_by_peer_total 17174
telemt_me_route_drop_no_conn_total 57183
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116911
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 16346
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 16043
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 116891
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 2203026488 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 58536769868 (54.52 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 73099.2 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141480
telemt_connections_bad_total 1700
telemt_handshake_timeouts_total 3301
telemt_upstream_connect_attempt_total 21318
telemt_upstream_connect_success_total 21310
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 21318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24948
telemt_me_reconnect_success_total 17588
telemt_me_reader_eof_total 18884
telemt_me_idle_close_by_peer_total 18884
telemt_me_route_drop_no_conn_total 55358
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124587
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 17986
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 17580
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 398
telemt_user_connections_total{user="hello"} 124479
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 10759950916 (10.02 GB)
telemt_user_octets_to_client{user="hello"} 69109563936 (64.36 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 73099.0 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196120
telemt_connections_bad_total 963
telemt_handshake_timeouts_total 1318
telemt_upstream_connect_attempt_total 17299
telemt_upstream_connect_success_total 17285
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 17299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8938
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13705
telemt_me_reconnect_success_total 13622
telemt_me_reader_eof_total 14502
telemt_me_idle_close_by_peer_total 14502
telemt_me_route_drop_no_conn_total 73964
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180836
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 643
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 402
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 301
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 13785
telemt_me_writer_restored_same_endpoint_total 13611
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 180748
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 3325124696 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 84748981344 (78.93 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 48171.5 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118658
telemt_connections_bad_total 24286
telemt_handshake_timeouts_total 2465
telemt_upstream_connect_attempt_total 14287
telemt_upstream_connect_success_total 14203
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 14287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 106054
telemt_me_reconnect_success_total 11608
telemt_me_reader_eof_total 12197
telemt_me_idle_close_by_peer_total 12197
telemt_me_route_drop_no_conn_total 40664
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88601
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 271
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 11677
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 11504
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 88733
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 1476275941 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 34299596771 (31.94 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 73099.5 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492769
telemt_connections_bad_total 57814
telemt_handshake_timeouts_total 4012
telemt_upstream_connect_attempt_total 15741
telemt_upstream_connect_success_total 15650
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13263
telemt_me_reconnect_success_total 11958
telemt_me_reader_eof_total 12705
telemt_me_idle_close_by_peer_total 12705
telemt_me_route_drop_no_conn_total 316174
telemt_me_route_drop_channel_closed_total 80
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 454302
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 12125
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11931
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 412879
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 10581007736 (9.85 GB)
telemt_user_octets_to_client{user="hello"} 226824110028 (211.25 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 66
```
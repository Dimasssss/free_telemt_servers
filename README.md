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

# Server Metrics 2026-03-12 15:06:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 27178.3 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144545
telemt_connections_bad_total 1597
telemt_handshake_timeouts_total 4581
telemt_upstream_connect_attempt_total 6638
telemt_upstream_connect_success_total 6612
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 276
telemt_me_reconnect_attempts_total 5227
telemt_me_reconnect_success_total 5191
telemt_me_reader_eof_total 5463
telemt_me_idle_close_by_peer_total 5462
telemt_me_route_drop_no_conn_total 41432
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125674
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 581
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 361
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5237
telemt_me_writer_restored_same_endpoint_total 5175
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 125636
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 2114001184 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 46547339664 (43.35 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 27071.2 (7h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60578
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 386
telemt_upstream_connect_attempt_total 8254
telemt_upstream_connect_success_total 8076
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 8254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 23630
telemt_me_reconnect_success_total 6707
telemt_me_reader_eof_total 7385
telemt_me_idle_close_by_peer_total 7385
telemt_me_route_drop_no_conn_total 26847
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57797
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
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
telemt_me_writer_removed_unexpected_total 7281
telemt_me_refill_failed_total 528
telemt_me_writer_restored_same_endpoint_total 6692
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 57788
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 640140560 (610.49 MB)
telemt_user_octets_to_client{user="hello"} 16276221784 (15.16 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 27034.7 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82558
telemt_connections_bad_total 1431
telemt_handshake_timeouts_total 1553
telemt_upstream_connect_attempt_total 7310
telemt_upstream_connect_success_total 7310
telemt_upstream_connect_attempts_per_request{bucket="1"} 7310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 5956
telemt_me_reconnect_success_total 5904
telemt_me_reader_eof_total 6236
telemt_me_idle_close_by_peer_total 6236
telemt_me_route_drop_no_conn_total 29364
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76138
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5953
telemt_me_writer_restored_same_endpoint_total 5884
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 76109
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 2030406032 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 41810508420 (38.94 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 27010.4 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109102
telemt_connections_bad_total 7298
telemt_handshake_timeouts_total 774
telemt_upstream_connect_attempt_total 6727
telemt_upstream_connect_success_total 6547
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 6727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 22317
telemt_me_reconnect_success_total 5177
telemt_me_reader_eof_total 5847
telemt_me_idle_close_by_peer_total 5847
telemt_me_route_drop_no_conn_total 38917
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95155
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5772
telemt_me_refill_failed_total 534
telemt_me_writer_restored_same_endpoint_total 5169
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 595
telemt_user_connections_total{user="hello"} 95038
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 1790113188 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 38817677760 (36.15 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 26979.9 (7h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62867
telemt_connections_bad_total 5231
telemt_handshake_timeouts_total 1058
telemt_upstream_connect_attempt_total 27022
telemt_upstream_connect_success_total 26693
telemt_upstream_connect_fail_total 329
telemt_upstream_connect_attempts_per_request{bucket="1"} 27022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 329
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 35583
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4677
telemt_me_idle_close_by_peer_total 4677
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12527
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33443
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 8
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
telemt_me_writer_removed_unexpected_total 4702
telemt_me_refill_failed_total 998
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1018
telemt_user_connections_total{user="hello"} 55083
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 466243756 (444.64 MB)
telemt_user_octets_to_client{user="hello"} 16859017039 (15.70 GB)
telemt_user_msgs_from_client{user="hello"} 336728
telemt_user_msgs_to_client{user="hello"} 1453691
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 26967.5 (7h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166965
telemt_connections_bad_total 895
telemt_handshake_timeouts_total 1272
telemt_upstream_connect_attempt_total 5545
telemt_upstream_connect_success_total 5517
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 4191
telemt_me_reconnect_success_total 4159
telemt_me_reader_eof_total 4373
telemt_me_idle_close_by_peer_total 4373
telemt_me_route_drop_no_conn_total 64818
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159713
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 242
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4208
telemt_me_writer_restored_same_endpoint_total 4152
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 159676
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 3206139276 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 73559660368 (68.51 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 55
```
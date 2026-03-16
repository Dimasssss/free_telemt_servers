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

# Server Metrics 2026-03-16 07:33:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 119960.1 (33h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 550215
telemt_connections_bad_total 5723
telemt_handshake_timeouts_total 19132
telemt_upstream_connect_attempt_total 28158
telemt_upstream_connect_success_total 28026
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 28158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25514
telemt_me_reconnect_success_total 22080
telemt_me_reader_eof_total 23627
telemt_me_idle_close_by_peer_total 23627
telemt_me_route_drop_no_conn_total 522981
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547704
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2662
telemt_desync_full_logged_total 1055
telemt_desync_suppressed_total 1607
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 1029
telemt_desync_frames_bucket_total{bucket="gt_10"} 1073
telemt_pool_swap_total 117
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22431
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22046
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 351
telemt_user_connections_total{user="hello"} 486526
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 9433746912 (8.79 GB)
telemt_user_octets_to_client{user="hello"} 316675502328 (294.93 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 119966.5 (33h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219286
telemt_connections_bad_total 3155
telemt_handshake_timeouts_total 15063
telemt_upstream_connect_attempt_total 32227
telemt_upstream_connect_success_total 32152
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 32227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 622
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 32702
telemt_me_reconnect_success_total 25783
telemt_me_reader_eof_total 27621
telemt_me_idle_close_by_peer_total 27620
telemt_me_route_drop_no_conn_total 107866
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193282
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 26349
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 25767
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 566
telemt_user_connections_total{user="hello"} 192831
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 4487925733 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 107974920932 (100.56 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 119959.1 (33h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237546
telemt_connections_bad_total 5731
telemt_handshake_timeouts_total 4596
telemt_upstream_connect_attempt_total 33397
telemt_upstream_connect_success_total 33389
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 33397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34776
telemt_me_reconnect_success_total 27374
telemt_me_reader_eof_total 29476
telemt_me_idle_close_by_peer_total 29475
telemt_me_route_drop_no_conn_total 83140
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189462
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 27871
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 27366
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 189174
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 17464024445 (16.26 GB)
telemt_user_octets_to_client{user="hello"} 111617671756 (103.95 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 119958.6 (33h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323415
telemt_connections_bad_total 1332
telemt_handshake_timeouts_total 2910
telemt_upstream_connect_attempt_total 27830
telemt_upstream_connect_success_total 27799
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 27830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14332
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 21967
telemt_me_reconnect_success_total 21831
telemt_me_reader_eof_total 23317
telemt_me_idle_close_by_peer_total 23316
telemt_me_route_drop_no_conn_total 114905
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298018
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1058
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 695
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 451
telemt_desync_frames_bucket_total{bucket="gt_10"} 387
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 22114
telemt_me_writer_restored_same_endpoint_total 21820
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 297899
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 4832404102 (4.50 GB)
telemt_user_octets_to_client{user="hello"} 128565970152 (119.74 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 95029.8 (26h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214186
telemt_connections_bad_total 35800
telemt_handshake_timeouts_total 3610
telemt_upstream_connect_attempt_total 27163
telemt_upstream_connect_success_total 27014
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 27163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 116618
telemt_me_reconnect_success_total 22128
telemt_me_reader_eof_total 23510
telemt_me_idle_close_by_peer_total 23510
telemt_me_route_drop_no_conn_total 67275
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169290
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 489
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 368
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 212
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 22309
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 22024
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 168919
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 2315706709 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 72420021815 (67.45 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 119958.2 (33h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 784588
telemt_connections_bad_total 68060
telemt_handshake_timeouts_total 6397
telemt_upstream_connect_attempt_total 25259
telemt_upstream_connect_success_total 25126
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 25259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13079
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20490
telemt_me_reconnect_success_total 19144
telemt_me_reader_eof_total 20449
telemt_me_idle_close_by_peer_total 20449
telemt_me_route_drop_no_conn_total 635391
telemt_me_route_drop_channel_closed_total 103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 786888
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
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 19411
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19117
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 645527
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 14268446088 (13.29 GB)
telemt_user_octets_to_client{user="hello"} 388723578844 (362.03 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 69
```
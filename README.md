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

# Server Metrics 2026-03-12 16:12:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 31173.3 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165221
telemt_connections_bad_total 2028
telemt_handshake_timeouts_total 4774
telemt_upstream_connect_attempt_total 7633
telemt_upstream_connect_success_total 7604
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 290
telemt_me_reconnect_attempts_total 6044
telemt_me_reconnect_success_total 5999
telemt_me_reader_eof_total 6304
telemt_me_idle_close_by_peer_total 6303
telemt_me_route_drop_no_conn_total 48042
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142048
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 616
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 387
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6057
telemt_me_writer_restored_same_endpoint_total 5983
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 142013
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 2390563332 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 54637354536 (50.89 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 31066.4 (8h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69116
telemt_connections_bad_total 457
telemt_handshake_timeouts_total 566
telemt_upstream_connect_attempt_total 10020
telemt_upstream_connect_success_total 9811
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 10020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 28935
telemt_me_reconnect_success_total 8232
telemt_me_reader_eof_total 9037
telemt_me_idle_close_by_peer_total 9037
telemt_me_route_drop_no_conn_total 30674
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65660
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
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
telemt_me_writer_removed_unexpected_total 8935
telemt_me_refill_failed_total 646
telemt_me_writer_restored_same_endpoint_total 8217
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 703
telemt_user_connections_total{user="hello"} 65651
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 724971680 (691.39 MB)
telemt_user_octets_to_client{user="hello"} 18514024584 (17.24 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 31029.7 (8h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94081
telemt_connections_bad_total 1488
telemt_handshake_timeouts_total 1907
telemt_upstream_connect_attempt_total 8519
telemt_upstream_connect_success_total 8519
telemt_upstream_connect_attempts_per_request{bucket="1"} 8519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4392
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 161
telemt_me_reconnect_attempts_total 6950
telemt_me_reconnect_success_total 6888
telemt_me_reader_eof_total 7285
telemt_me_idle_close_by_peer_total 7285
telemt_me_route_drop_no_conn_total 34559
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86801
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6948
telemt_me_writer_restored_same_endpoint_total 6868
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 86775
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 2168317480 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 44050539164 (41.03 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 31005.4 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128906
telemt_connections_bad_total 13051
telemt_handshake_timeouts_total 977
telemt_upstream_connect_attempt_total 7140
telemt_upstream_connect_success_total 6925
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 7140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 302
telemt_me_reconnect_attempts_total 29292
telemt_me_reconnect_success_total 5334
telemt_me_reader_eof_total 6217
telemt_me_idle_close_by_peer_total 6217
telemt_me_route_drop_no_conn_total 45295
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108186
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 376
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 262
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6144
telemt_me_refill_failed_total 747
telemt_me_writer_restored_same_endpoint_total 5326
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 810
telemt_user_connections_total{user="hello"} 108066
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 2075600116 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 46061356112 (42.90 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 30974.9 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73245
telemt_connections_bad_total 6367
telemt_handshake_timeouts_total 1087
telemt_upstream_connect_attempt_total 35663
telemt_upstream_connect_success_total 35279
telemt_upstream_connect_fail_total 384
telemt_upstream_connect_attempts_per_request{bucket="1"} 35663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 384
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 42415
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4891
telemt_me_idle_close_by_peer_total 4891
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12736
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34123
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 10
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
telemt_me_writer_removed_unexpected_total 4917
telemt_me_refill_failed_total 1213
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1233
telemt_user_connections_total{user="hello"} 64126
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 571385480 (544.92 MB)
telemt_user_octets_to_client{user="hello"} 19387014562 (18.06 GB)
telemt_user_msgs_from_client{user="hello"} 480865
telemt_user_msgs_to_client{user="hello"} 1893211
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 30962.4 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193731
telemt_connections_bad_total 953
telemt_handshake_timeouts_total 1515
telemt_upstream_connect_attempt_total 6614
telemt_upstream_connect_success_total 6581
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 6614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 364
telemt_me_reconnect_attempts_total 6058
telemt_me_reconnect_success_total 4990
telemt_me_reader_eof_total 5261
telemt_me_idle_close_by_peer_total 5260
telemt_me_route_drop_no_conn_total 75069
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185454
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5087
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4983
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 185407
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 3541954260 (3.30 GB)
telemt_user_octets_to_client{user="hello"} 82074334636 (76.44 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 71
```
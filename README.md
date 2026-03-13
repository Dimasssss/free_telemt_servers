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

# Server Metrics 2026-03-13 15:45:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 115947.0 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481521
telemt_connections_bad_total 3450
telemt_handshake_timeouts_total 8831
telemt_upstream_connect_attempt_total 28947
telemt_upstream_connect_success_total 28810
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2480
telemt_me_reconnect_attempts_total 26557
telemt_me_reconnect_success_total 23022
telemt_me_reader_eof_total 24594
telemt_me_idle_close_by_peer_total 24593
telemt_me_route_drop_no_conn_total 157273
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 422678
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1375
telemt_desync_full_logged_total 484
telemt_desync_suppressed_total 891
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 23375
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23006
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 353
telemt_user_connections_total{user="hello"} 422255
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 7538857904 (7.02 GB)
telemt_user_octets_to_client{user="hello"} 196901833508 (183.38 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 115840.0 (32h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231629
telemt_connections_bad_total 1840
telemt_handshake_timeouts_total 1677
telemt_upstream_connect_attempt_total 88604
telemt_upstream_connect_success_total 87821
telemt_upstream_connect_fail_total 783
telemt_upstream_connect_attempts_per_request{bucket="1"} 88604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 985
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 783
telemt_me_keepalive_timeout_total 1407
telemt_me_reconnect_attempts_total 114930
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29558
telemt_me_idle_close_by_peer_total 29558
telemt_me_route_drop_no_conn_total 81615
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163278
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29024
telemt_me_refill_failed_total 2774
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3002
telemt_user_connections_total{user="hello"} 219083
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 2225682237 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 68952835920 (64.22 GB)
telemt_user_msgs_from_client{user="hello"} 847446
telemt_user_msgs_to_client{user="hello"} 5339166
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 115803.6 (32h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279025
telemt_connections_bad_total 2437
telemt_handshake_timeouts_total 13172
telemt_upstream_connect_attempt_total 31047
telemt_upstream_connect_success_total 31043
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 31047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2346
telemt_me_reconnect_attempts_total 26435
telemt_me_reconnect_success_total 25214
telemt_me_reader_eof_total 27024
telemt_me_idle_close_by_peer_total 27024
telemt_me_route_drop_no_conn_total 100941
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253480
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 25494
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25194
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 253396
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 9652734856 (8.99 GB)
telemt_user_octets_to_client{user="hello"} 107572794820 (100.18 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 115778.9 (32h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379607
telemt_connections_bad_total 15048
telemt_handshake_timeouts_total 3768
telemt_upstream_connect_attempt_total 42976
telemt_upstream_connect_success_total 32802
telemt_upstream_connect_fail_total 10174
telemt_upstream_connect_attempts_per_request{bucket="1"} 42976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16074
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10174
telemt_me_keepalive_timeout_total 4166
telemt_me_reconnect_attempts_total 104044
telemt_me_reconnect_success_total 23972
telemt_me_reader_eof_total 27182
telemt_me_idle_close_by_peer_total 27175
telemt_me_route_drop_no_conn_total 136027
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329212
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1322
telemt_desync_full_logged_total 391
telemt_desync_suppressed_total 931
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 501
telemt_desync_frames_bucket_total{bucket="gt_10"} 497
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26781
telemt_me_refill_failed_total 2497
telemt_me_writer_restored_same_endpoint_total 23962
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2809
telemt_user_connections_total{user="hello"} 332123
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 6923785234 (6.45 GB)
telemt_user_octets_to_client{user="hello"} 124000342713 (115.48 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 65950.5 (18h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103031
telemt_connections_bad_total 13181
telemt_handshake_timeouts_total 1309
telemt_upstream_connect_attempt_total 26732
telemt_upstream_connect_success_total 26499
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 26732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 1048
telemt_me_reconnect_attempts_total 29451
telemt_me_reconnect_success_total 18279
telemt_me_reader_eof_total 19610
telemt_me_idle_close_by_peer_total 19610
telemt_me_route_drop_no_conn_total 31481
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80308
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 18783
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 18261
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 504
telemt_user_connections_total{user="hello"} 85207
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 976223277 (931.00 MB)
telemt_user_octets_to_client{user="hello"} 26118281459 (24.32 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 115736.2 (32h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 699248
telemt_connections_bad_total 23239
telemt_handshake_timeouts_total 22991
telemt_upstream_connect_attempt_total 24270
telemt_upstream_connect_success_total 24148
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 24270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12805
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 2555
telemt_me_reconnect_attempts_total 23027
telemt_me_reconnect_success_total 18399
telemt_me_reader_eof_total 19744
telemt_me_idle_close_by_peer_total 19741
telemt_me_route_drop_no_conn_total 330977
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 657010
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 658
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 448
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 18778
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18392
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 629960
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 10635454196 (9.91 GB)
telemt_user_octets_to_client{user="hello"} 325333024064 (302.99 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 67
```
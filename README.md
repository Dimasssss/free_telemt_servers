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

# Server Metrics 2026-03-13 15:30:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 115029.8 (31h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477660
telemt_connections_bad_total 3322
telemt_handshake_timeouts_total 8671
telemt_upstream_connect_attempt_total 28778
telemt_upstream_connect_success_total 28641
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2477
telemt_me_reconnect_attempts_total 26431
telemt_me_reconnect_success_total 22897
telemt_me_reader_eof_total 24462
telemt_me_idle_close_by_peer_total 24461
telemt_me_route_drop_no_conn_total 156000
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 419362
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1373
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 890
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 579
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 23247
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22881
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 350
telemt_user_connections_total{user="hello"} 418939
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 7493336820 (6.98 GB)
telemt_user_octets_to_client{user="hello"} 194907983684 (181.52 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 114922.9 (31h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229116
telemt_connections_bad_total 1839
telemt_handshake_timeouts_total 1585
telemt_upstream_connect_attempt_total 86339
telemt_upstream_connect_success_total 85562
telemt_upstream_connect_fail_total 777
telemt_upstream_connect_attempts_per_request{bucket="1"} 86339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 941
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 777
telemt_me_keepalive_timeout_total 1407
telemt_me_reconnect_attempts_total 113554
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29515
telemt_me_idle_close_by_peer_total 29515
telemt_me_route_drop_no_conn_total 81415
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163120
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
telemt_me_writer_removed_unexpected_total 28981
telemt_me_refill_failed_total 2731
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2959
telemt_user_connections_total{user="hello"} 216709
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 2195627666 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 68541989234 (63.83 GB)
telemt_user_msgs_from_client{user="hello"} 809434
telemt_user_msgs_to_client{user="hello"} 5186510
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 114887.0 (31h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276445
telemt_connections_bad_total 2432
telemt_handshake_timeouts_total 12799
telemt_upstream_connect_attempt_total 30836
telemt_upstream_connect_success_total 30832
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16509
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2344
telemt_me_reconnect_attempts_total 26267
telemt_me_reconnect_success_total 25046
telemt_me_reader_eof_total 26842
telemt_me_idle_close_by_peer_total 26842
telemt_me_route_drop_no_conn_total 99897
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251365
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
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 25322
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25026
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 251279
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 9586274620 (8.93 GB)
telemt_user_octets_to_client{user="hello"} 107172022556 (99.81 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 114862.1 (31h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376310
telemt_connections_bad_total 15047
telemt_handshake_timeouts_total 3743
telemt_upstream_connect_attempt_total 42813
telemt_upstream_connect_success_total 32648
telemt_upstream_connect_fail_total 10165
telemt_upstream_connect_attempts_per_request{bucket="1"} 42813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15987
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10165
telemt_me_keepalive_timeout_total 4164
telemt_me_reconnect_attempts_total 102621
telemt_me_reconnect_success_total 23861
telemt_me_reader_eof_total 27028
telemt_me_idle_close_by_peer_total 27021
telemt_me_route_drop_no_conn_total 135041
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326141
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1297
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 911
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 486
telemt_desync_frames_bucket_total{bucket="gt_10"} 490
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26627
telemt_me_refill_failed_total 2456
telemt_me_writer_restored_same_endpoint_total 23851
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2766
telemt_user_connections_total{user="hello"} 329051
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 6909009826 (6.43 GB)
telemt_user_octets_to_client{user="hello"} 123558667913 (115.07 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 65033.7 (18h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101457
telemt_connections_bad_total 13014
telemt_handshake_timeouts_total 1250
telemt_upstream_connect_attempt_total 26501
telemt_upstream_connect_success_total 26274
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 26501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 1046
telemt_me_reconnect_attempts_total 29269
telemt_me_reconnect_success_total 18097
telemt_me_reader_eof_total 19416
telemt_me_idle_close_by_peer_total 19416
telemt_me_route_drop_no_conn_total 30883
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79001
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
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 18600
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 18079
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 83900
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 965697909 (920.96 MB)
telemt_user_octets_to_client{user="hello"} 25870359667 (24.09 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 114819.2 (31h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691187
telemt_connections_bad_total 21968
telemt_handshake_timeouts_total 22453
telemt_upstream_connect_attempt_total 24098
telemt_upstream_connect_success_total 23976
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 24098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 2553
telemt_me_reconnect_attempts_total 22898
telemt_me_reconnect_success_total 18272
telemt_me_reader_eof_total 19609
telemt_me_idle_close_by_peer_total 19606
telemt_me_route_drop_no_conn_total 328351
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 650990
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 604
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 401
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 18651
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18265
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 623941
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 10594653680 (9.87 GB)
telemt_user_octets_to_client{user="hello"} 323066863468 (300.88 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 61
```
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

# Server Metrics 2026-03-14 06:11:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 167904.6 (46h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 645859
telemt_connections_bad_total 32325
telemt_handshake_timeouts_total 13015
telemt_upstream_connect_attempt_total 42777
telemt_upstream_connect_success_total 42561
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 42777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22989
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5606
telemt_me_reconnect_attempts_total 38499
telemt_me_reconnect_success_total 33810
telemt_me_reader_eof_total 36153
telemt_me_idle_close_by_peer_total 36152
telemt_me_route_drop_no_conn_total 211769
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547997
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1973
telemt_desync_full_logged_total 676
telemt_desync_suppressed_total 1297
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 823
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 34323
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33790
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 513
telemt_user_connections_total{user="hello"} 547882
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 16051643078 (14.95 GB)
telemt_user_octets_to_client{user="hello"} 265952943144 (247.69 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 167797.6 (46h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325835
telemt_connections_bad_total 2289
telemt_handshake_timeouts_total 2397
telemt_upstream_connect_attempt_total 149413
telemt_upstream_connect_success_total 148166
telemt_upstream_connect_fail_total 1247
telemt_upstream_connect_attempts_per_request{bucket="1"} 149413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1247
telemt_me_keepalive_timeout_total 3970
telemt_me_reconnect_attempts_total 175801
telemt_me_reconnect_success_total 36489
telemt_me_reader_eof_total 41804
telemt_me_idle_close_by_peer_total 41804
telemt_me_route_drop_no_conn_total 105302
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205543
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 41187
telemt_me_refill_failed_total 4347
telemt_me_writer_restored_same_endpoint_total 36472
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4698
telemt_user_connections_total{user="hello"} 308653
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 3194277983 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 100713223895 (93.80 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 167761.2 (46h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379829
telemt_connections_bad_total 2966
telemt_handshake_timeouts_total 34941
telemt_upstream_connect_attempt_total 44407
telemt_upstream_connect_success_total 44398
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24064
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3468
telemt_me_reconnect_attempts_total 37276
telemt_me_reconnect_success_total 35991
telemt_me_reader_eof_total 38705
telemt_me_idle_close_by_peer_total 38705
telemt_me_route_drop_no_conn_total 136884
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 328746
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 36425
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 35970
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 434
telemt_user_connections_total{user="hello"} 328519
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 13369420148 (12.45 GB)
telemt_user_octets_to_client{user="hello"} 130177743776 (121.24 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 167736.8 (46h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480681
telemt_connections_bad_total 15655
telemt_handshake_timeouts_total 4485
telemt_upstream_connect_attempt_total 74610
telemt_upstream_connect_success_total 64047
telemt_upstream_connect_fail_total 10563
telemt_upstream_connect_attempts_per_request{bucket="1"} 74610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10563
telemt_me_keepalive_timeout_total 5382
telemt_me_reconnect_attempts_total 142707
telemt_me_reconnect_success_total 36649
telemt_me_reader_eof_total 41123
telemt_me_idle_close_by_peer_total 41115
telemt_me_route_drop_no_conn_total 173277
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408748
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1750
telemt_desync_full_logged_total 517
telemt_desync_suppressed_total 1233
telemt_desync_frames_bucket_total{bucket="1_2"} 415
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 670
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 40384
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 36639
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3735
telemt_user_connections_total{user="hello"} 427589
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 9266977627 (8.63 GB)
telemt_user_octets_to_client{user="hello"} 170901467044 (159.16 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 117908.4 (32h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192689
telemt_connections_bad_total 28567
telemt_handshake_timeouts_total 1666
telemt_upstream_connect_attempt_total 41953
telemt_upstream_connect_success_total 41558
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 41953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_keepalive_timeout_total 2448
telemt_me_reconnect_attempts_total 44247
telemt_me_reconnect_success_total 30822
telemt_me_reader_eof_total 32984
telemt_me_idle_close_by_peer_total 32984
telemt_me_route_drop_no_conn_total 57143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152325
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 623
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 31524
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30804
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 702
telemt_user_connections_total{user="hello"} 157074
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 2353475345 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 71439725043 (66.53 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 167692.9 (46h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 957329
telemt_connections_bad_total 35995
telemt_handshake_timeouts_total 25912
telemt_upstream_connect_attempt_total 34827
telemt_upstream_connect_success_total 34640
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 34827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_timeout_total 4686
telemt_me_reconnect_attempts_total 31011
telemt_me_reconnect_success_total 26334
telemt_me_reader_eof_total 28271
telemt_me_idle_close_by_peer_total 28268
telemt_me_route_drop_no_conn_total 451372
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 887334
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 26815
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26327
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 859985
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 14879969132 (13.86 GB)
telemt_user_octets_to_client{user="hello"} 437527291448 (407.48 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 55
```
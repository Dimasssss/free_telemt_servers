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

# Server Metrics 2026-03-18 05:51:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 126390.9 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1509038
telemt_connections_bad_total 10647
telemt_handshake_timeouts_total 35690
telemt_upstream_connect_attempt_total 27497
telemt_upstream_connect_success_total 26978
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 27497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 35548
telemt_me_reconnect_success_total 18397
telemt_me_reader_eof_total 19952
telemt_me_idle_close_by_peer_total 19951
telemt_me_route_drop_no_conn_total 616314
telemt_me_route_drop_channel_closed_total 167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1339512
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8186
telemt_desync_full_logged_total 2466
telemt_desync_suppressed_total 5720
telemt_desync_frames_bucket_total{bucket="1_2"} 2141
telemt_desync_frames_bucket_total{bucket="3_10"} 3152
telemt_desync_frames_bucket_total{bucket="gt_10"} 2893
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 19208
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18375
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 811
telemt_user_connections_total{user="hello"} 1333739
telemt_user_connections_current{user="hello"} 921
telemt_user_octets_from_client{user="hello"} 31982371127 (29.79 GB)
telemt_user_octets_to_client{user="hello"} 478349633831 (445.50 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 126642.2 (35h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1621113
telemt_connections_bad_total 76964
telemt_handshake_timeouts_total 52880
telemt_upstream_connect_attempt_total 470970
telemt_upstream_connect_success_total 469336
telemt_upstream_connect_fail_total 1634
telemt_upstream_connect_attempts_per_request{bucket="1"} 470970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34806
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1634
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126852
telemt_me_reconnect_success_total 20121
telemt_me_reader_eof_total 22415
telemt_me_idle_close_by_peer_total 22402
telemt_me_route_drop_no_conn_total 426919
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 971289
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4421
telemt_desync_full_logged_total 1530
telemt_desync_suppressed_total 2891
telemt_desync_frames_bucket_total{bucket="1_2"} 871
telemt_desync_frames_bucket_total{bucket="3_10"} 1777
telemt_desync_frames_bucket_total{bucket="gt_10"} 1773
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 21750
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20103
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1629
telemt_user_connections_total{user="hello"} 1413656
telemt_user_connections_current{user="hello"} 1645
telemt_user_octets_from_client{user="hello"} 19575661129 (18.23 GB)
telemt_user_octets_to_client{user="hello"} 541788541258 (504.58 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 126477.8 (35h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1509912
telemt_connections_bad_total 74436
telemt_handshake_timeouts_total 26313
telemt_upstream_connect_attempt_total 91895
telemt_upstream_connect_success_total 89445
telemt_upstream_connect_fail_total 2450
telemt_upstream_connect_attempts_per_request{bucket="1"} 91895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15118
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2450
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38805
telemt_me_reconnect_success_total 18385
telemt_me_reader_eof_total 20162
telemt_me_idle_close_by_peer_total 20159
telemt_me_route_drop_no_conn_total 605751
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1233291
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4786
telemt_desync_full_logged_total 1555
telemt_desync_suppressed_total 3231
telemt_desync_frames_bucket_total{bucket="1_2"} 1132
telemt_desync_frames_bucket_total{bucket="3_10"} 2001
telemt_desync_frames_bucket_total{bucket="gt_10"} 1653
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 19365
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18365
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 980
telemt_user_connections_total{user="hello"} 1296564
telemt_user_connections_current{user="hello"} 1692
telemt_user_octets_from_client{user="hello"} 21131275954 (19.68 GB)
telemt_user_octets_to_client{user="hello"} 635883306018 (592.21 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 126449.6 (35h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1066389
telemt_connections_bad_total 105794
telemt_handshake_timeouts_total 10400
telemt_upstream_connect_attempt_total 48840
telemt_upstream_connect_success_total 48166
telemt_upstream_connect_fail_total 674
telemt_upstream_connect_attempts_per_request{bucket="1"} 48840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 424
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 674
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60363
telemt_me_reconnect_success_total 25395
telemt_me_reader_eof_total 27470
telemt_me_idle_close_by_peer_total 27467
telemt_me_route_drop_no_conn_total 343215
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 875380
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3777
telemt_desync_full_logged_total 1164
telemt_desync_suppressed_total 2613
telemt_desync_frames_bucket_total{bucket="1_2"} 1095
telemt_desync_frames_bucket_total{bucket="3_10"} 1465
telemt_desync_frames_bucket_total{bucket="gt_10"} 1217
telemt_pool_swap_total 68
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26880
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25387
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1485
telemt_user_connections_total{user="hello"} 891842
telemt_user_connections_current{user="hello"} 1525
telemt_user_octets_from_client{user="hello"} 16877697660 (15.72 GB)
telemt_user_octets_to_client{user="hello"} 447117657160 (416.41 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 507
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 126610.9 (35h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1217956
telemt_connections_bad_total 127794
telemt_handshake_timeouts_total 10598
telemt_upstream_connect_attempt_total 25159
telemt_upstream_connect_success_total 25012
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 25159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 30026
telemt_me_reconnect_success_total 18730
telemt_me_reader_eof_total 20291
telemt_me_idle_close_by_peer_total 20289
telemt_me_route_drop_no_conn_total 828625
telemt_me_route_drop_channel_closed_total 91
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1195965
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2275
telemt_desync_full_logged_total 798
telemt_desync_suppressed_total 1477
telemt_desync_frames_bucket_total{bucket="1_2"} 509
telemt_desync_frames_bucket_total{bucket="3_10"} 864
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 115
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19369
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18716
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 639
telemt_user_connections_total{user="hello"} 1004646
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 15956592644 (14.86 GB)
telemt_user_octets_to_client{user="hello"} 446638595220 (415.96 GB)
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 74377.7 (20h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 580366
telemt_connections_bad_total 55921
telemt_handshake_timeouts_total 13575
telemt_upstream_connect_attempt_total 25778
telemt_upstream_connect_success_total 25511
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 25778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 33282
telemt_me_reconnect_success_total 21667
telemt_me_reader_eof_total 22894
telemt_me_idle_close_by_peer_total 22894
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 143173
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423623
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1854
telemt_desync_full_logged_total 622
telemt_desync_suppressed_total 1232
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 824
telemt_desync_frames_bucket_total{bucket="gt_10"} 723
telemt_pool_swap_total 52
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22258
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21623
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 591
telemt_user_connections_total{user="hello"} 423376
telemt_user_connections_current{user="hello"} 1042
telemt_user_octets_from_client{user="hello"} 26619698713 (24.79 GB)
telemt_user_octets_to_client{user="hello"} 331001342830 (308.27 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 123
```
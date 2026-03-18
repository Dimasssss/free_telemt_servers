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

# Server Metrics 2026-03-18 02:38:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 114785.6 (31h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1324043
telemt_connections_bad_total 10147
telemt_handshake_timeouts_total 33179
telemt_upstream_connect_attempt_total 25494
telemt_upstream_connect_success_total 24987
telemt_upstream_connect_fail_total 507
telemt_upstream_connect_attempts_per_request{bucket="1"} 25494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 507
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34116
telemt_me_reconnect_success_total 16976
telemt_me_reader_eof_total 18428
telemt_me_idle_close_by_peer_total 18427
telemt_me_route_drop_no_conn_total 571706
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1218852
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7773
telemt_desync_full_logged_total 2302
telemt_desync_suppressed_total 5471
telemt_desync_frames_bucket_total{bucket="1_2"} 2072
telemt_desync_frames_bucket_total{bucket="3_10"} 2963
telemt_desync_frames_bucket_total{bucket="gt_10"} 2738
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 17764
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16954
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 788
telemt_user_connections_total{user="hello"} 1213066
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 24650849775 (22.96 GB)
telemt_user_octets_to_client{user="hello"} 428567959227 (399.14 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 115036.6 (31h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1396389
telemt_connections_bad_total 64254
telemt_handshake_timeouts_total 47223
telemt_upstream_connect_attempt_total 468410
telemt_upstream_connect_success_total 466829
telemt_upstream_connect_fail_total 1581
telemt_upstream_connect_attempts_per_request{bucket="1"} 468410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1581
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 123625
telemt_me_reconnect_success_total 18184
telemt_me_reader_eof_total 20358
telemt_me_idle_close_by_peer_total 20345
telemt_me_route_drop_no_conn_total 359949
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 772097
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3620
telemt_desync_full_logged_total 1239
telemt_desync_suppressed_total 2381
telemt_desync_frames_bucket_total{bucket="1_2"} 714
telemt_desync_frames_bucket_total{bucket="3_10"} 1507
telemt_desync_frames_bucket_total{bucket="gt_10"} 1399
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 19751
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 18166
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1567
telemt_user_connections_total{user="hello"} 1214447
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 16369379169 (15.25 GB)
telemt_user_octets_to_client{user="hello"} 426695837902 (397.39 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 114812.5 (31h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 845791
telemt_connections_bad_total 59020
telemt_handshake_timeouts_total 24678
telemt_upstream_connect_attempt_total 26819
telemt_upstream_connect_success_total 26664
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 26819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14339
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41592
telemt_me_reconnect_success_total 20899
telemt_me_reader_eof_total 22738
telemt_me_idle_close_by_peer_total 22731
telemt_me_route_drop_no_conn_total 333262
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711322
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2240
telemt_desync_full_logged_total 727
telemt_desync_suppressed_total 1513
telemt_desync_frames_bucket_total{bucket="1_2"} 640
telemt_desync_frames_bucket_total{bucket="3_10"} 870
telemt_desync_frames_bucket_total{bucket="gt_10"} 730
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 21825
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20887
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 926
telemt_user_connections_total{user="hello"} 709440
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 44057046968 (41.03 GB)
telemt_user_octets_to_client{user="hello"} 316822041856 (295.06 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 114871.9 (31h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1323054
telemt_connections_bad_total 60023
telemt_handshake_timeouts_total 22125
telemt_upstream_connect_attempt_total 89559
telemt_upstream_connect_success_total 87145
telemt_upstream_connect_fail_total 2414
telemt_upstream_connect_attempts_per_request{bucket="1"} 89559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2414
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37054
telemt_me_reconnect_success_total 16658
telemt_me_reader_eof_total 18346
telemt_me_idle_close_by_peer_total 18344
telemt_me_route_drop_no_conn_total 543260
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1074800
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3986
telemt_desync_full_logged_total 1320
telemt_desync_suppressed_total 2666
telemt_desync_frames_bucket_total{bucket="1_2"} 974
telemt_desync_frames_bucket_total{bucket="3_10"} 1673
telemt_desync_frames_bucket_total{bucket="gt_10"} 1339
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17609
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16647
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 951
telemt_user_connections_total{user="hello"} 1138174
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 17824045386 (16.60 GB)
telemt_user_octets_to_client{user="hello"} 539786580378 (502.72 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 114843.8 (31h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 882836
telemt_connections_bad_total 100968
telemt_handshake_timeouts_total 6927
telemt_upstream_connect_attempt_total 46379
telemt_upstream_connect_success_total 45747
telemt_upstream_connect_fail_total 632
telemt_upstream_connect_attempts_per_request{bucket="1"} 46379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 632
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58504
telemt_me_reconnect_success_total 23541
telemt_me_reader_eof_total 25519
telemt_me_idle_close_by_peer_total 25516
telemt_me_route_drop_no_conn_total 281512
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 713501
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3282
telemt_desync_full_logged_total 980
telemt_desync_suppressed_total 2302
telemt_desync_frames_bucket_total{bucket="1_2"} 1028
telemt_desync_frames_bucket_total{bucket="3_10"} 1310
telemt_desync_frames_bucket_total{bucket="gt_10"} 944
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25008
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23533
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1467
telemt_user_connections_total{user="hello"} 730060
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 13967668676 (13.01 GB)
telemt_user_octets_to_client{user="hello"} 359784059068 (335.08 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 115004.8 (31h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1130709
telemt_connections_bad_total 123230
telemt_handshake_timeouts_total 9907
telemt_upstream_connect_attempt_total 22882
telemt_upstream_connect_success_total 22752
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 22882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11715
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28325
telemt_me_reconnect_success_total 17036
telemt_me_reader_eof_total 18473
telemt_me_idle_close_by_peer_total 18471
telemt_me_route_drop_no_conn_total 779735
telemt_me_route_drop_channel_closed_total 89
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1105169
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 102
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17658
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17022
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 926475
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 14948944132 (13.92 GB)
telemt_user_octets_to_client{user="hello"} 405055838056 (377.24 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 62772.2 (17h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433045
telemt_connections_bad_total 44767
telemt_handshake_timeouts_total 11560
telemt_upstream_connect_attempt_total 23094
telemt_upstream_connect_success_total 22870
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 23094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31201
telemt_me_reconnect_success_total 19593
telemt_me_reader_eof_total 20715
telemt_me_idle_close_by_peer_total 20715
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 106539
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313418
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1375
telemt_desync_full_logged_total 440
telemt_desync_suppressed_total 935
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 621
telemt_desync_frames_bucket_total{bucket="gt_10"} 525
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20173
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19554
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 313354
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 22656208301 (21.10 GB)
telemt_user_octets_to_client{user="hello"} 263084918010 (245.02 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 33
```
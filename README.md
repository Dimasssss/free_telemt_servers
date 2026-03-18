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

# Server Metrics 2026-03-18 01:21:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 110202.4 (30h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1285285
telemt_connections_bad_total 9612
telemt_handshake_timeouts_total 32513
telemt_upstream_connect_attempt_total 24631
telemt_upstream_connect_success_total 24130
telemt_upstream_connect_fail_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 24631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 501
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33478
telemt_me_reconnect_success_total 16340
telemt_me_reader_eof_total 17744
telemt_me_idle_close_by_peer_total 17743
telemt_me_route_drop_no_conn_total 562219
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1182540
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7586
telemt_desync_full_logged_total 2230
telemt_desync_suppressed_total 5356
telemt_desync_frames_bucket_total{bucket="1_2"} 2030
telemt_desync_frames_bucket_total{bucket="3_10"} 2879
telemt_desync_frames_bucket_total{bucket="gt_10"} 2677
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17118
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16318
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 778
telemt_user_connections_total{user="hello"} 1176752
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 22856831807 (21.29 GB)
telemt_user_octets_to_client{user="hello"} 419564149175 (390.75 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 110453.8 (30h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1361896
telemt_connections_bad_total 63885
telemt_handshake_timeouts_total 46510
telemt_upstream_connect_attempt_total 467207
telemt_upstream_connect_success_total 465656
telemt_upstream_connect_fail_total 1551
telemt_upstream_connect_attempts_per_request{bucket="1"} 467207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1551
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122665
telemt_me_reconnect_success_total 17235
telemt_me_reader_eof_total 19378
telemt_me_idle_close_by_peer_total 19368
telemt_me_route_drop_no_conn_total 351099
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 739981
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3435
telemt_desync_full_logged_total 1152
telemt_desync_suppressed_total 2283
telemt_desync_frames_bucket_total{bucket="1_2"} 672
telemt_desync_frames_bucket_total{bucket="3_10"} 1420
telemt_desync_frames_bucket_total{bucket="gt_10"} 1343
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 18786
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17217
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1551
telemt_user_connections_total{user="hello"} 1182331
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 16072825221 (14.97 GB)
telemt_user_octets_to_client{user="hello"} 409011346598 (380.92 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 110229.6 (30h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 810435
telemt_connections_bad_total 54327
telemt_handshake_timeouts_total 24254
telemt_upstream_connect_attempt_total 25846
telemt_upstream_connect_success_total 25699
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 25846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13811
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40839
telemt_me_reconnect_success_total 20153
telemt_me_reader_eof_total 21944
telemt_me_idle_close_by_peer_total 21937
telemt_me_route_drop_no_conn_total 325341
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 687677
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2190
telemt_desync_full_logged_total 711
telemt_desync_suppressed_total 1479
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 848
telemt_desync_frames_bucket_total{bucket="gt_10"} 721
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 21072
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20141
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 919
telemt_user_connections_total{user="hello"} 685796
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 39269445232 (36.57 GB)
telemt_user_octets_to_client{user="hello"} 302929532796 (282.13 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 110289.0 (30h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1293172
telemt_connections_bad_total 55418
telemt_handshake_timeouts_total 21943
telemt_upstream_connect_attempt_total 86938
telemt_upstream_connect_success_total 85513
telemt_upstream_connect_fail_total 1424
telemt_upstream_connect_attempts_per_request{bucket="1"} 86937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1424
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 36363
telemt_me_reconnect_success_total 16000
telemt_me_reader_eof_total 17644
telemt_me_idle_close_by_peer_total 17642
telemt_me_route_drop_no_conn_total 528036
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1052089
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3954
telemt_desync_full_logged_total 1307
telemt_desync_suppressed_total 2647
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 1660
telemt_desync_frames_bucket_total{bucket="gt_10"} 1328
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 16935
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15990
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 935
telemt_user_connections_total{user="hello"} 1115208
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 17484007283 (16.28 GB)
telemt_user_octets_to_client{user="hello"} 527417131942 (491.20 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 110260.9 (30h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 852800
telemt_connections_bad_total 99736
telemt_handshake_timeouts_total 6838
telemt_upstream_connect_attempt_total 45352
telemt_upstream_connect_success_total 44729
telemt_upstream_connect_fail_total 623
telemt_upstream_connect_attempts_per_request{bucket="1"} 45352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 623
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 57701
telemt_me_reconnect_success_total 22740
telemt_me_reader_eof_total 24661
telemt_me_idle_close_by_peer_total 24659
telemt_me_route_drop_no_conn_total 271289
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 687301
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3182
telemt_desync_full_logged_total 946
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 1006
telemt_desync_frames_bucket_total{bucket="3_10"} 1273
telemt_desync_frames_bucket_total{bucket="gt_10"} 903
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24196
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 22732
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1456
telemt_user_connections_total{user="hello"} 703907
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 13655115556 (12.72 GB)
telemt_user_octets_to_client{user="hello"} 350666701336 (326.58 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 110422.0 (30h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1098432
telemt_connections_bad_total 110975
telemt_handshake_timeouts_total 9675
telemt_upstream_connect_attempt_total 21954
telemt_upstream_connect_success_total 21833
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 21954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27620
telemt_me_reconnect_success_total 16336
telemt_me_reader_eof_total 17731
telemt_me_idle_close_by_peer_total 17729
telemt_me_route_drop_no_conn_total 745802
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1067523
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
telemt_pool_swap_total 97
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16949
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16322
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 907469
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 14728711988 (13.72 GB)
telemt_user_octets_to_client{user="hello"} 390497720760 (363.68 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 58189.1 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406528
telemt_connections_bad_total 44693
telemt_handshake_timeouts_total 10931
telemt_upstream_connect_attempt_total 21760
telemt_upstream_connect_success_total 21561
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 21760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30105
telemt_me_reconnect_success_total 18503
telemt_me_reader_eof_total 19571
telemt_me_idle_close_by_peer_total 19571
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 100984
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297031
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1226
telemt_desync_full_logged_total 377
telemt_desync_suppressed_total 849
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 538
telemt_desync_frames_bucket_total{bucket="gt_10"} 469
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19073
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 18469
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 296967
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 22448698389 (20.91 GB)
telemt_user_octets_to_client{user="hello"} 248140150294 (231.10 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 25
```
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

# Server Metrics 2026-03-18 02:53:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 115702.2 (32h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1330507
telemt_connections_bad_total 10365
telemt_handshake_timeouts_total 33216
telemt_upstream_connect_attempt_total 25662
telemt_upstream_connect_success_total 25153
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 25662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34239
telemt_me_reconnect_success_total 17098
telemt_me_reader_eof_total 18556
telemt_me_idle_close_by_peer_total 18555
telemt_me_route_drop_no_conn_total 573348
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1224843
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7785
telemt_desync_full_logged_total 2311
telemt_desync_suppressed_total 5474
telemt_desync_frames_bucket_total{bucket="1_2"} 2072
telemt_desync_frames_bucket_total{bucket="3_10"} 2970
telemt_desync_frames_bucket_total{bucket="gt_10"} 2743
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 17888
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17076
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 790
telemt_user_connections_total{user="hello"} 1219055
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 24731412043 (23.03 GB)
telemt_user_octets_to_client{user="hello"} 431691787171 (402.04 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 115953.3 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1404793
telemt_connections_bad_total 64557
telemt_handshake_timeouts_total 47375
telemt_upstream_connect_attempt_total 468747
telemt_upstream_connect_success_total 467162
telemt_upstream_connect_fail_total 1585
telemt_upstream_connect_attempts_per_request{bucket="1"} 468747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33651
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1585
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 123915
telemt_me_reconnect_success_total 18474
telemt_me_reader_eof_total 20650
telemt_me_idle_close_by_peer_total 20637
telemt_me_route_drop_no_conn_total 362041
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 779872
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3649
telemt_desync_full_logged_total 1254
telemt_desync_suppressed_total 2395
telemt_desync_frames_bucket_total{bucket="1_2"} 718
telemt_desync_frames_bucket_total{bucket="3_10"} 1523
telemt_desync_frames_bucket_total{bucket="gt_10"} 1408
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 20043
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 18456
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1569
telemt_user_connections_total{user="hello"} 1222217
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 16451030233 (15.32 GB)
telemt_user_octets_to_client{user="hello"} 431045073186 (401.44 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 115729.3 (32h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 853306
telemt_connections_bad_total 60040
telemt_handshake_timeouts_total 24742
telemt_upstream_connect_attempt_total 26989
telemt_upstream_connect_success_total 26833
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 26989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14436
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41718
telemt_me_reconnect_success_total 21022
telemt_me_reader_eof_total 22871
telemt_me_idle_close_by_peer_total 22864
telemt_me_route_drop_no_conn_total 334865
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 717321
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2247
telemt_desync_full_logged_total 730
telemt_desync_suppressed_total 1517
telemt_desync_frames_bucket_total{bucket="1_2"} 645
telemt_desync_frames_bucket_total{bucket="3_10"} 872
telemt_desync_frames_bucket_total{bucket="gt_10"} 730
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 21952
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21010
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 930
telemt_user_connections_total{user="hello"} 715437
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 44155590880 (41.12 GB)
telemt_user_octets_to_client{user="hello"} 319770211116 (297.81 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 115788.8 (32h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1330256
telemt_connections_bad_total 60902
telemt_handshake_timeouts_total 22483
telemt_upstream_connect_attempt_total 89809
telemt_upstream_connect_success_total 87387
telemt_upstream_connect_fail_total 2422
telemt_upstream_connect_attempts_per_request{bucket="1"} 89809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 371
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2422
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37259
telemt_me_reconnect_success_total 16856
telemt_me_reader_eof_total 18543
telemt_me_idle_close_by_peer_total 18540
telemt_me_route_drop_no_conn_total 545525
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1080420
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4010
telemt_desync_full_logged_total 1325
telemt_desync_suppressed_total 2685
telemt_desync_frames_bucket_total{bucket="1_2"} 980
telemt_desync_frames_bucket_total{bucket="3_10"} 1677
telemt_desync_frames_bucket_total{bucket="gt_10"} 1353
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17809
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16836
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 953
telemt_user_connections_total{user="hello"} 1143794
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 17880834098 (16.65 GB)
telemt_user_octets_to_client{user="hello"} 542695883574 (505.42 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 115760.8 (32h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 889589
telemt_connections_bad_total 101140
telemt_handshake_timeouts_total 6978
telemt_upstream_connect_attempt_total 46628
telemt_upstream_connect_success_total 45990
telemt_upstream_connect_fail_total 638
telemt_upstream_connect_attempts_per_request{bucket="1"} 46628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 638
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58704
telemt_me_reconnect_success_total 23741
telemt_me_reader_eof_total 25720
telemt_me_idle_close_by_peer_total 25717
telemt_me_route_drop_no_conn_total 283624
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 719489
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3300
telemt_desync_full_logged_total 991
telemt_desync_suppressed_total 2309
telemt_desync_frames_bucket_total{bucket="1_2"} 1029
telemt_desync_frames_bucket_total{bucket="3_10"} 1317
telemt_desync_frames_bucket_total{bucket="gt_10"} 954
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25209
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23733
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1468
telemt_user_connections_total{user="hello"} 736045
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 14025487300 (13.06 GB)
telemt_user_octets_to_client{user="hello"} 363716283984 (338.74 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 115921.5 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1137581
telemt_connections_bad_total 125686
telemt_handshake_timeouts_total 10107
telemt_upstream_connect_attempt_total 23058
telemt_upstream_connect_success_total 22927
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 23058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28457
telemt_me_reconnect_success_total 17167
telemt_me_reader_eof_total 18612
telemt_me_idle_close_by_peer_total 18610
telemt_me_route_drop_no_conn_total 784319
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1111572
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2107
telemt_desync_full_logged_total 738
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 803
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 103
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17789
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17153
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 930583
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 14976061568 (13.95 GB)
telemt_user_octets_to_client{user="hello"} 407127799256 (379.17 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 63688.9 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438189
telemt_connections_bad_total 44800
telemt_handshake_timeouts_total 11663
telemt_upstream_connect_attempt_total 23313
telemt_upstream_connect_success_total 23084
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 23313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31372
telemt_me_reconnect_success_total 19764
telemt_me_reader_eof_total 20898
telemt_me_idle_close_by_peer_total 20898
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 107871
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317361
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1386
telemt_desync_full_logged_total 446
telemt_desync_suppressed_total 940
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 627
telemt_desync_frames_bucket_total{bucket="gt_10"} 528
telemt_pool_swap_total 42
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20344
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19725
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 317297
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 22703323925 (21.14 GB)
telemt_user_octets_to_client{user="hello"} 265720400666 (247.47 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 40
```
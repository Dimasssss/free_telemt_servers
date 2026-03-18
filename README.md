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

# Server Metrics 2026-03-18 04:45:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 122422.8 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1399291
telemt_connections_bad_total 10541
telemt_handshake_timeouts_total 34214
telemt_upstream_connect_attempt_total 26825
telemt_upstream_connect_success_total 26312
telemt_upstream_connect_fail_total 513
telemt_upstream_connect_attempts_per_request{bucket="1"} 26825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 513
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 35095
telemt_me_reconnect_success_total 17948
telemt_me_reader_eof_total 19467
telemt_me_idle_close_by_peer_total 19466
telemt_me_route_drop_no_conn_total 597014
telemt_me_route_drop_channel_closed_total 164
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1287289
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7993
telemt_desync_full_logged_total 2390
telemt_desync_suppressed_total 5603
telemt_desync_frames_bucket_total{bucket="1_2"} 2108
telemt_desync_frames_bucket_total{bucket="3_10"} 3063
telemt_desync_frames_bucket_total{bucket="gt_10"} 2822
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 18749
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17926
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 801
telemt_user_connections_total{user="hello"} 1281505
telemt_user_connections_current{user="hello"} 818
telemt_user_octets_from_client{user="hello"} 26792712015 (24.95 GB)
telemt_user_octets_to_client{user="hello"} 453854385071 (422.68 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 122674.4 (34h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1516788
telemt_connections_bad_total 73755
telemt_handshake_timeouts_total 50269
telemt_upstream_connect_attempt_total 470309
telemt_upstream_connect_success_total 468686
telemt_upstream_connect_fail_total 1623
telemt_upstream_connect_attempts_per_request{bucket="1"} 470309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1623
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126375
telemt_me_reconnect_success_total 19646
telemt_me_reader_eof_total 21918
telemt_me_idle_close_by_peer_total 21905
telemt_me_route_drop_no_conn_total 394751
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 877022
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3940
telemt_desync_full_logged_total 1368
telemt_desync_suppressed_total 2572
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 1612
telemt_desync_frames_bucket_total{bucket="gt_10"} 1553
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 21268
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19628
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1622
telemt_user_connections_total{user="hello"} 1319339
telemt_user_connections_current{user="hello"} 1229
telemt_user_octets_from_client{user="hello"} 17865791365 (16.64 GB)
telemt_user_octets_to_client{user="hello"} 490816809690 (457.11 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 122450.3 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 953928
telemt_connections_bad_total 67249
telemt_handshake_timeouts_total 27684
telemt_upstream_connect_attempt_total 28211
telemt_upstream_connect_success_total 28051
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 28211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15091
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42615
telemt_me_reconnect_success_total 21915
telemt_me_reader_eof_total 23822
telemt_me_idle_close_by_peer_total 23815
telemt_me_route_drop_no_conn_total 358786
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 787299
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2548
telemt_desync_full_logged_total 840
telemt_desync_suppressed_total 1708
telemt_desync_frames_bucket_total{bucket="1_2"} 710
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 865
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 22853
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21903
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 938
telemt_user_connections_total{user="hello"} 785400
telemt_user_connections_current{user="hello"} 895
telemt_user_octets_from_client{user="hello"} 45141656080 (42.04 GB)
telemt_user_octets_to_client{user="hello"} 364908024456 (339.85 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 122509.7 (34h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1410486
telemt_connections_bad_total 69129
telemt_handshake_timeouts_total 24457
telemt_upstream_connect_attempt_total 91245
telemt_upstream_connect_success_total 88807
telemt_upstream_connect_fail_total 2438
telemt_upstream_connect_attempts_per_request{bucket="1"} 91245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2438
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38335
telemt_me_reconnect_success_total 17925
telemt_me_reader_eof_total 19672
telemt_me_idle_close_by_peer_total 19669
telemt_me_route_drop_no_conn_total 572498
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1147792
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4324
telemt_desync_full_logged_total 1418
telemt_desync_suppressed_total 2906
telemt_desync_frames_bucket_total{bucket="1_2"} 1057
telemt_desync_frames_bucket_total{bucket="3_10"} 1815
telemt_desync_frames_bucket_total{bucket="gt_10"} 1452
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 18891
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17905
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 966
telemt_user_connections_total{user="hello"} 1211096
telemt_user_connections_current{user="hello"} 1163
telemt_user_octets_from_client{user="hello"} 18913817938 (17.61 GB)
telemt_user_octets_to_client{user="hello"} 586268229338 (546.00 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 380
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 122481.6 (34h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 975843
telemt_connections_bad_total 102730
telemt_handshake_timeouts_total 9263
telemt_upstream_connect_attempt_total 48133
telemt_upstream_connect_success_total 47469
telemt_upstream_connect_fail_total 664
telemt_upstream_connect_attempts_per_request{bucket="1"} 48133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17690
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 664
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59858
telemt_me_reconnect_success_total 24892
telemt_me_reader_eof_total 26935
telemt_me_idle_close_by_peer_total 26932
telemt_me_route_drop_no_conn_total 311641
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 794622
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3552
telemt_desync_full_logged_total 1075
telemt_desync_suppressed_total 2477
telemt_desync_frames_bucket_total{bucket="1_2"} 1062
telemt_desync_frames_bucket_total{bucket="3_10"} 1391
telemt_desync_frames_bucket_total{bucket="gt_10"} 1099
telemt_pool_swap_total 64
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26368
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24884
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1476
telemt_user_connections_total{user="hello"} 811100
telemt_user_connections_current{user="hello"} 1066
telemt_user_octets_from_client{user="hello"} 15545716916 (14.48 GB)
telemt_user_octets_to_client{user="hello"} 412178818668 (383.87 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 381
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 122642.7 (34h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1180629
telemt_connections_bad_total 127202
telemt_handshake_timeouts_total 10369
telemt_upstream_connect_attempt_total 24442
telemt_upstream_connect_success_total 24301
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 24442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12515
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29487
telemt_me_reconnect_success_total 18193
telemt_me_reader_eof_total 19721
telemt_me_idle_close_by_peer_total 19719
telemt_me_route_drop_no_conn_total 814392
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1161793
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2178
telemt_desync_full_logged_total 765
telemt_desync_suppressed_total 1413
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 874
telemt_pool_swap_total 111
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18829
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18179
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 970481
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 15428800904 (14.37 GB)
telemt_user_octets_to_client{user="hello"} 427905783168 (398.52 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 70410.0 (19h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 514292
telemt_connections_bad_total 52834
telemt_handshake_timeouts_total 12944
telemt_upstream_connect_attempt_total 25051
telemt_upstream_connect_success_total 24795
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 25051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32739
telemt_me_reconnect_success_total 21128
telemt_me_reader_eof_total 22332
telemt_me_idle_close_by_peer_total 22332
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 124988
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368520
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1616
telemt_desync_full_logged_total 532
telemt_desync_suppressed_total 1084
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 721
telemt_desync_frames_bucket_total{bucket="gt_10"} 623
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21716
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21085
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 368272
telemt_user_connections_current{user="hello"} 762
telemt_user_octets_from_client{user="hello"} 23612549137 (21.99 GB)
telemt_user_octets_to_client{user="hello"} 296287693230 (275.94 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 90
```
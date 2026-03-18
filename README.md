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

# Server Metrics 2026-03-18 04:20:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 120895.5 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1379893
telemt_connections_bad_total 10523
telemt_handshake_timeouts_total 33948
telemt_upstream_connect_attempt_total 26620
telemt_upstream_connect_success_total 26108
telemt_upstream_connect_fail_total 512
telemt_upstream_connect_attempts_per_request{bucket="1"} 26620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 512
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34936
telemt_me_reconnect_success_total 17790
telemt_me_reader_eof_total 19301
telemt_me_idle_close_by_peer_total 19300
telemt_me_route_drop_no_conn_total 591035
telemt_me_route_drop_channel_closed_total 162
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1270854
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7961
telemt_desync_full_logged_total 2375
telemt_desync_suppressed_total 5586
telemt_desync_frames_bucket_total{bucket="1_2"} 2105
telemt_desync_frames_bucket_total{bucket="3_10"} 3046
telemt_desync_frames_bucket_total{bucket="gt_10"} 2810
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18589
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17768
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 799
telemt_user_connections_total{user="hello"} 1265063
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 25520145319 (23.77 GB)
telemt_user_octets_to_client{user="hello"} 447277658467 (416.56 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 121146.9 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1485316
telemt_connections_bad_total 70938
telemt_handshake_timeouts_total 48373
telemt_upstream_connect_attempt_total 469962
telemt_upstream_connect_success_total 468350
telemt_upstream_connect_fail_total 1612
telemt_upstream_connect_attempts_per_request{bucket="1"} 469962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1612
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126125
telemt_me_reconnect_success_total 19399
telemt_me_reader_eof_total 21657
telemt_me_idle_close_by_peer_total 21644
telemt_me_route_drop_no_conn_total 385054
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 850262
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3829
telemt_desync_full_logged_total 1328
telemt_desync_suppressed_total 2501
telemt_desync_frames_bucket_total{bucket="1_2"} 750
telemt_desync_frames_bucket_total{bucket="3_10"} 1575
telemt_desync_frames_bucket_total{bucket="gt_10"} 1504
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 21018
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19381
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1619
telemt_user_connections_total{user="hello"} 1292577
telemt_user_connections_current{user="hello"} 1200
telemt_user_octets_from_client{user="hello"} 17490315365 (16.29 GB)
telemt_user_octets_to_client{user="hello"} 473423620518 (440.91 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 120922.9 (33h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 924188
telemt_connections_bad_total 64841
telemt_handshake_timeouts_total 26451
telemt_upstream_connect_attempt_total 27981
telemt_upstream_connect_success_total 27821
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 27981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42446
telemt_me_reconnect_success_total 21748
telemt_me_reader_eof_total 23646
telemt_me_idle_close_by_peer_total 23639
telemt_me_route_drop_no_conn_total 351835
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 766288
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2425
telemt_desync_full_logged_total 796
telemt_desync_suppressed_total 1629
telemt_desync_frames_bucket_total{bucket="1_2"} 694
telemt_desync_frames_bucket_total{bucket="3_10"} 939
telemt_desync_frames_bucket_total{bucket="gt_10"} 792
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 22683
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21736
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 935
telemt_user_connections_total{user="hello"} 764401
telemt_user_connections_current{user="hello"} 921
telemt_user_octets_from_client{user="hello"} 44848011008 (41.77 GB)
telemt_user_octets_to_client{user="hello"} 351693516052 (327.54 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 120982.3 (33h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1383806
telemt_connections_bad_total 66440
telemt_handshake_timeouts_total 24223
telemt_upstream_connect_attempt_total 91008
telemt_upstream_connect_success_total 88571
telemt_upstream_connect_fail_total 2437
telemt_upstream_connect_attempts_per_request{bucket="1"} 91008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14682
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2437
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38185
telemt_me_reconnect_success_total 17776
telemt_me_reader_eof_total 19516
telemt_me_idle_close_by_peer_total 19513
telemt_me_route_drop_no_conn_total 564836
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1125031
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4171
telemt_desync_full_logged_total 1377
telemt_desync_suppressed_total 2794
telemt_desync_frames_bucket_total{bucket="1_2"} 1030
telemt_desync_frames_bucket_total{bucket="3_10"} 1742
telemt_desync_frames_bucket_total{bucket="gt_10"} 1399
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 18739
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17756
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 963
telemt_user_connections_total{user="hello"} 1188338
telemt_user_connections_current{user="hello"} 996
telemt_user_octets_from_client{user="hello"} 18536263974 (17.26 GB)
telemt_user_octets_to_client{user="hello"} 572984599338 (533.63 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 120954.1 (33h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 947580
telemt_connections_bad_total 102265
telemt_handshake_timeouts_total 8128
telemt_upstream_connect_attempt_total 47838
telemt_upstream_connect_success_total 47179
telemt_upstream_connect_fail_total 659
telemt_upstream_connect_attempts_per_request{bucket="1"} 47838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 659
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59635
telemt_me_reconnect_success_total 24670
telemt_me_reader_eof_total 26696
telemt_me_idle_close_by_peer_total 26693
telemt_me_route_drop_no_conn_total 302387
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 771036
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3455
telemt_desync_full_logged_total 1046
telemt_desync_suppressed_total 2409
telemt_desync_frames_bucket_total{bucket="1_2"} 1044
telemt_desync_frames_bucket_total{bucket="3_10"} 1360
telemt_desync_frames_bucket_total{bucket="gt_10"} 1051
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26145
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24662
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1475
telemt_user_connections_total{user="hello"} 787549
telemt_user_connections_current{user="hello"} 1035
telemt_user_octets_from_client{user="hello"} 14998932868 (13.97 GB)
telemt_user_octets_to_client{user="hello"} 396279979604 (369.06 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 121115.1 (33h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1169118
telemt_connections_bad_total 126869
telemt_handshake_timeouts_total 10321
telemt_upstream_connect_attempt_total 24133
telemt_upstream_connect_success_total 23994
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 24133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12361
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29266
telemt_me_reconnect_success_total 17972
telemt_me_reader_eof_total 19484
telemt_me_idle_close_by_peer_total 19482
telemt_me_route_drop_no_conn_total 810327
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1151240
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2146
telemt_desync_full_logged_total 754
telemt_desync_suppressed_total 1392
telemt_desync_frames_bucket_total{bucket="1_2"} 472
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 862
telemt_pool_swap_total 109
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18604
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17958
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 959930
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 15290762116 (14.24 GB)
telemt_user_octets_to_client{user="hello"} 423446398252 (394.37 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 68882.4 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493741
telemt_connections_bad_total 52186
telemt_handshake_timeouts_total 12710
telemt_upstream_connect_attempt_total 24662
telemt_upstream_connect_success_total 24413
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 24662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32443
telemt_me_reconnect_success_total 20832
telemt_me_reader_eof_total 22023
telemt_me_idle_close_by_peer_total 22023
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 118432
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353189
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1536
telemt_desync_full_logged_total 503
telemt_desync_suppressed_total 1033
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 690
telemt_desync_frames_bucket_total{bucket="gt_10"} 593
telemt_pool_swap_total 47
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21418
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20789
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 586
telemt_user_connections_total{user="hello"} 352982
telemt_user_connections_current{user="hello"} 767
telemt_user_octets_from_client{user="hello"} 23394897669 (21.79 GB)
telemt_user_octets_to_client{user="hello"} 287729141902 (267.97 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 83
```
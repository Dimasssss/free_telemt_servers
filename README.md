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

# Server Metrics 2026-03-18 05:56:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 126696.4 (35h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1518544
telemt_connections_bad_total 10669
telemt_handshake_timeouts_total 35748
telemt_upstream_connect_attempt_total 27529
telemt_upstream_connect_success_total 27010
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 27529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12967
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 35580
telemt_me_reconnect_success_total 18429
telemt_me_reader_eof_total 19984
telemt_me_idle_close_by_peer_total 19983
telemt_me_route_drop_no_conn_total 618000
telemt_me_route_drop_channel_closed_total 167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1343919
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8207
telemt_desync_full_logged_total 2472
telemt_desync_suppressed_total 5735
telemt_desync_frames_bucket_total{bucket="1_2"} 2152
telemt_desync_frames_bucket_total{bucket="3_10"} 3159
telemt_desync_frames_bucket_total{bucket="gt_10"} 2896
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 19240
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18407
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 811
telemt_user_connections_total{user="hello"} 1338142
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 32012635987 (29.81 GB)
telemt_user_octets_to_client{user="hello"} 480516119719 (447.52 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 126948.0 (35h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1631066
telemt_connections_bad_total 77780
telemt_handshake_timeouts_total 53015
telemt_upstream_connect_attempt_total 471013
telemt_upstream_connect_success_total 469379
telemt_upstream_connect_fail_total 1634
telemt_upstream_connect_attempts_per_request{bucket="1"} 471013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1634
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126885
telemt_me_reconnect_success_total 20154
telemt_me_reader_eof_total 22448
telemt_me_idle_close_by_peer_total 22435
telemt_me_route_drop_no_conn_total 429689
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 980056
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4450
telemt_desync_full_logged_total 1542
telemt_desync_suppressed_total 2908
telemt_desync_frames_bucket_total{bucket="1_2"} 872
telemt_desync_frames_bucket_total{bucket="3_10"} 1791
telemt_desync_frames_bucket_total{bucket="gt_10"} 1787
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 21783
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20136
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1629
telemt_user_connections_total{user="hello"} 1422430
telemt_user_connections_current{user="hello"} 1704
telemt_user_octets_from_client{user="hello"} 19676027317 (18.32 GB)
telemt_user_octets_to_client{user="hello"} 546484619546 (508.95 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 603
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 126723.9 (35h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1114533
telemt_connections_bad_total 74818
telemt_handshake_timeouts_total 30022
telemt_upstream_connect_attempt_total 28873
telemt_upstream_connect_success_total 28709
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 28873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 43075
telemt_me_reconnect_success_total 22371
telemt_me_reader_eof_total 24311
telemt_me_idle_close_by_peer_total 24304
telemt_me_route_drop_no_conn_total 387807
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 863749
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2913
telemt_desync_full_logged_total 954
telemt_desync_suppressed_total 1959
telemt_desync_frames_bucket_total{bucket="1_2"} 788
telemt_desync_frames_bucket_total{bucket="3_10"} 1139
telemt_desync_frames_bucket_total{bucket="gt_10"} 986
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 23319
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22359
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 948
telemt_user_connections_total{user="hello"} 861846
telemt_user_connections_current{user="hello"} 1370
telemt_user_octets_from_client{user="hello"} 46580545820 (43.38 GB)
telemt_user_octets_to_client{user="hello"} 419163989888 (390.38 GB)
telemt_user_unique_ips_current{user="hello"} 434
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 126783.6 (35h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1518991
telemt_connections_bad_total 74826
telemt_handshake_timeouts_total 26514
telemt_upstream_connect_attempt_total 91933
telemt_upstream_connect_success_total 89483
telemt_upstream_connect_fail_total 2450
telemt_upstream_connect_attempts_per_request{bucket="1"} 91933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2450
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38843
telemt_me_reconnect_success_total 18422
telemt_me_reader_eof_total 20199
telemt_me_idle_close_by_peer_total 20196
telemt_me_route_drop_no_conn_total 609603
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1241466
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4814
telemt_desync_full_logged_total 1565
telemt_desync_suppressed_total 3249
telemt_desync_frames_bucket_total{bucket="1_2"} 1141
telemt_desync_frames_bucket_total{bucket="3_10"} 2007
telemt_desync_frames_bucket_total{bucket="gt_10"} 1666
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 19402
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18402
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 980
telemt_user_connections_total{user="hello"} 1304740
telemt_user_connections_current{user="hello"} 1836
telemt_user_octets_from_client{user="hello"} 21503785538 (20.03 GB)
telemt_user_octets_to_client{user="hello"} 640230036626 (596.26 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 503
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 126755.2 (35h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1074784
telemt_connections_bad_total 105868
telemt_handshake_timeouts_total 10542
telemt_upstream_connect_attempt_total 48858
telemt_upstream_connect_success_total 48184
telemt_upstream_connect_fail_total 674
telemt_upstream_connect_attempts_per_request{bucket="1"} 48858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 424
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 674
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60380
telemt_me_reconnect_success_total 25412
telemt_me_reader_eof_total 27487
telemt_me_idle_close_by_peer_total 27484
telemt_me_route_drop_no_conn_total 345665
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 882904
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3818
telemt_desync_full_logged_total 1179
telemt_desync_suppressed_total 2639
telemt_desync_frames_bucket_total{bucket="1_2"} 1101
telemt_desync_frames_bucket_total{bucket="3_10"} 1481
telemt_desync_frames_bucket_total{bucket="gt_10"} 1236
telemt_pool_swap_total 68
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26897
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25404
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1485
telemt_user_connections_total{user="hello"} 899364
telemt_user_connections_current{user="hello"} 1565
telemt_user_octets_from_client{user="hello"} 17037210184 (15.87 GB)
telemt_user_octets_to_client{user="hello"} 450573746504 (419.63 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 126916.8 (35h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1221609
telemt_connections_bad_total 127836
telemt_handshake_timeouts_total 10616
telemt_upstream_connect_attempt_total 25176
telemt_upstream_connect_success_total 25029
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 25176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 30043
telemt_me_reconnect_success_total 18747
telemt_me_reader_eof_total 20310
telemt_me_idle_close_by_peer_total 20308
telemt_me_route_drop_no_conn_total 829796
telemt_me_route_drop_channel_closed_total 91
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1199319
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
telemt_me_writer_removed_unexpected_total 19388
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18733
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 641
telemt_user_connections_total{user="hello"} 1008000
telemt_user_connections_current{user="hello"} 765
telemt_user_octets_from_client{user="hello"} 16014313316 (14.91 GB)
telemt_user_octets_to_client{user="hello"} 447284520520 (416.57 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 74683.5 (20h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 586222
telemt_connections_bad_total 56324
telemt_handshake_timeouts_total 13589
telemt_upstream_connect_attempt_total 25799
telemt_upstream_connect_success_total 25532
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 25799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 33303
telemt_me_reconnect_success_total 21687
telemt_me_reader_eof_total 22917
telemt_me_idle_close_by_peer_total 22917
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 144666
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428589
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1265
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 838
telemt_desync_frames_bucket_total{bucket="gt_10"} 739
telemt_pool_swap_total 52
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22281
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21643
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 428342
telemt_user_connections_current{user="hello"} 1045
telemt_user_octets_from_client{user="hello"} 26715516437 (24.88 GB)
telemt_user_octets_to_client{user="hello"} 334209878314 (311.26 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 128
```
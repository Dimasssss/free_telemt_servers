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

# Server Metrics 2026-03-18 05:31:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 125169.3 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1473268
telemt_connections_bad_total 10582
telemt_handshake_timeouts_total 35319
telemt_upstream_connect_attempt_total 27272
telemt_upstream_connect_success_total 26755
telemt_upstream_connect_fail_total 517
telemt_upstream_connect_attempts_per_request{bucket="1"} 27272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 517
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 35384
telemt_me_reconnect_success_total 18235
telemt_me_reader_eof_total 19775
telemt_me_idle_close_by_peer_total 19774
telemt_me_route_drop_no_conn_total 610318
telemt_me_route_drop_channel_closed_total 167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1324031
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8123
telemt_desync_full_logged_total 2441
telemt_desync_suppressed_total 5682
telemt_desync_frames_bucket_total{bucket="1_2"} 2134
telemt_desync_frames_bucket_total{bucket="3_10"} 3121
telemt_desync_frames_bucket_total{bucket="gt_10"} 2868
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 19043
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18213
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 808
telemt_user_connections_total{user="hello"} 1318260
telemt_user_connections_current{user="hello"} 879
telemt_user_octets_from_client{user="hello"} 31402103203 (29.25 GB)
telemt_user_octets_to_client{user="hello"} 470649389051 (438.33 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 125420.8 (34h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1584210
telemt_connections_bad_total 75457
telemt_handshake_timeouts_total 52104
telemt_upstream_connect_attempt_total 470750
telemt_upstream_connect_success_total 469124
telemt_upstream_connect_fail_total 1626
telemt_upstream_connect_attempts_per_request{bucket="1"} 470750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1626
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126683
telemt_me_reconnect_success_total 19954
telemt_me_reader_eof_total 22245
telemt_me_idle_close_by_peer_total 22232
telemt_me_route_drop_no_conn_total 415722
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 938295
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4182
telemt_desync_full_logged_total 1453
telemt_desync_suppressed_total 2729
telemt_desync_frames_bucket_total{bucket="1_2"} 826
telemt_desync_frames_bucket_total{bucket="3_10"} 1703
telemt_desync_frames_bucket_total{bucket="gt_10"} 1653
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 21580
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19936
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1626
telemt_user_connections_total{user="hello"} 1380645
telemt_user_connections_current{user="hello"} 1566
telemt_user_octets_from_client{user="hello"} 19039672285 (17.73 GB)
telemt_user_octets_to_client{user="hello"} 524797785774 (488.76 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 539
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 125196.8 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1044930
telemt_connections_bad_total 72470
telemt_handshake_timeouts_total 28509
telemt_upstream_connect_attempt_total 28656
telemt_upstream_connect_success_total 28494
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 28656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15314
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42903
telemt_me_reconnect_success_total 22201
telemt_me_reader_eof_total 24129
telemt_me_idle_close_by_peer_total 24122
telemt_me_route_drop_no_conn_total 376313
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 833529
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2817
telemt_desync_full_logged_total 918
telemt_desync_suppressed_total 1899
telemt_desync_frames_bucket_total{bucket="1_2"} 776
telemt_desync_frames_bucket_total{bucket="3_10"} 1094
telemt_desync_frames_bucket_total{bucket="gt_10"} 947
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 23146
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22189
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 945
telemt_user_connections_total{user="hello"} 831629
telemt_user_connections_current{user="hello"} 1327
telemt_user_octets_from_client{user="hello"} 45948020944 (42.79 GB)
telemt_user_octets_to_client{user="hello"} 400132224244 (372.65 GB)
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 125256.1 (34h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1474714
telemt_connections_bad_total 72504
telemt_handshake_timeouts_total 25319
telemt_upstream_connect_attempt_total 91666
telemt_upstream_connect_success_total 89220
telemt_upstream_connect_fail_total 2446
telemt_upstream_connect_attempts_per_request{bucket="1"} 91666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14996
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2446
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38622
telemt_me_reconnect_success_total 18206
telemt_me_reader_eof_total 19978
telemt_me_idle_close_by_peer_total 19975
telemt_me_route_drop_no_conn_total 594637
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1203389
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4646
telemt_desync_full_logged_total 1514
telemt_desync_suppressed_total 3132
telemt_desync_frames_bucket_total{bucket="1_2"} 1107
telemt_desync_frames_bucket_total{bucket="3_10"} 1937
telemt_desync_frames_bucket_total{bucket="gt_10"} 1602
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 19182
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18186
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 976
telemt_user_connections_total{user="hello"} 1266667
telemt_user_connections_current{user="hello"} 1556
telemt_user_octets_from_client{user="hello"} 20727161278 (19.30 GB)
telemt_user_octets_to_client{user="hello"} 619446239266 (576.90 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 479
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 125227.9 (34h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1035143
telemt_connections_bad_total 104461
telemt_handshake_timeouts_total 10126
telemt_upstream_connect_attempt_total 48658
telemt_upstream_connect_success_total 47986
telemt_upstream_connect_fail_total 672
telemt_upstream_connect_attempts_per_request{bucket="1"} 48658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 424
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 672
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60227
telemt_me_reconnect_success_total 25260
telemt_me_reader_eof_total 27327
telemt_me_idle_close_by_peer_total 27324
telemt_me_route_drop_no_conn_total 332718
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 847405
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3721
telemt_desync_full_logged_total 1141
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1086
telemt_desync_frames_bucket_total{bucket="3_10"} 1444
telemt_desync_frames_bucket_total{bucket="gt_10"} 1191
telemt_pool_swap_total 67
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26741
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25252
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1481
telemt_user_connections_total{user="hello"} 863880
telemt_user_connections_current{user="hello"} 1376
telemt_user_octets_from_client{user="hello"} 16532520572 (15.40 GB)
telemt_user_octets_to_client{user="hello"} 435915154388 (405.98 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 472
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 125388.9 (34h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1203983
telemt_connections_bad_total 127614
telemt_handshake_timeouts_total 10504
telemt_upstream_connect_attempt_total 24968
telemt_upstream_connect_success_total 24821
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 24968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29878
telemt_me_reconnect_success_total 18584
telemt_me_reader_eof_total 20138
telemt_me_idle_close_by_peer_total 20136
telemt_me_route_drop_no_conn_total 823511
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1183039
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2262
telemt_desync_full_logged_total 790
telemt_desync_suppressed_total 1472
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 860
telemt_desync_frames_bucket_total{bucket="gt_10"} 897
telemt_pool_swap_total 114
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19222
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18570
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 991720
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 15757995508 (14.68 GB)
telemt_user_octets_to_client{user="hello"} 442580920344 (412.19 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 73156.2 (20h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 558477
telemt_connections_bad_total 54359
telemt_handshake_timeouts_total 13448
telemt_upstream_connect_attempt_total 25569
telemt_upstream_connect_success_total 25303
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 25569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 33118
telemt_me_reconnect_success_total 21504
telemt_me_reader_eof_total 22726
telemt_me_idle_close_by_peer_total 22726
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 137179
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 405102
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1761
telemt_desync_full_logged_total 582
telemt_desync_suppressed_total 1179
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 782
telemt_desync_frames_bucket_total{bucket="gt_10"} 687
telemt_pool_swap_total 51
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22094
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21461
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 590
telemt_user_connections_total{user="hello"} 404857
telemt_user_connections_current{user="hello"} 1066
telemt_user_octets_from_client{user="hello"} 25397290733 (23.65 GB)
telemt_user_octets_to_client{user="hello"} 317649669758 (295.83 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 119
```
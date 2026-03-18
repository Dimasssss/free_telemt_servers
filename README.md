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

# Server Metrics 2026-03-18 06:12:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 127612.6 (35h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1550839
telemt_connections_bad_total 10690
telemt_handshake_timeouts_total 36122
telemt_upstream_connect_attempt_total 27707
telemt_upstream_connect_success_total 27188
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 27707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 35712
telemt_me_reconnect_success_total 18560
telemt_me_reader_eof_total 20119
telemt_me_idle_close_by_peer_total 20118
telemt_me_route_drop_no_conn_total 624026
telemt_me_route_drop_channel_closed_total 171
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1358945
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8292
telemt_desync_full_logged_total 2499
telemt_desync_suppressed_total 5793
telemt_desync_frames_bucket_total{bucket="1_2"} 2171
telemt_desync_frames_bucket_total{bucket="3_10"} 3187
telemt_desync_frames_bucket_total{bucket="gt_10"} 2934
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 19375
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18538
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 815
telemt_user_connections_total{user="hello"} 1353169
telemt_user_connections_current{user="hello"} 1093
telemt_user_octets_from_client{user="hello"} 32218867815 (30.01 GB)
telemt_user_octets_to_client{user="hello"} 486369302679 (452.97 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 127864.1 (35h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1666558
telemt_connections_bad_total 80299
telemt_handshake_timeouts_total 53852
telemt_upstream_connect_attempt_total 471166
telemt_upstream_connect_success_total 469530
telemt_upstream_connect_fail_total 1636
telemt_upstream_connect_attempts_per_request{bucket="1"} 471166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34899
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1636
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126986
telemt_me_reconnect_success_total 20253
telemt_me_reader_eof_total 22560
telemt_me_idle_close_by_peer_total 22547
telemt_me_route_drop_no_conn_total 442218
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1011002
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4630
telemt_desync_full_logged_total 1605
telemt_desync_suppressed_total 3025
telemt_desync_frames_bucket_total{bucket="1_2"} 901
telemt_desync_frames_bucket_total{bucket="3_10"} 1860
telemt_desync_frames_bucket_total{bucket="gt_10"} 1869
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 21885
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20235
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1632
telemt_user_connections_total{user="hello"} 1453357
telemt_user_connections_current{user="hello"} 1932
telemt_user_octets_from_client{user="hello"} 20201585601 (18.81 GB)
telemt_user_octets_to_client{user="hello"} 562165887390 (523.56 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 633
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 127640.1 (35h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1158373
telemt_connections_bad_total 76520
telemt_handshake_timeouts_total 30611
telemt_upstream_connect_attempt_total 29007
telemt_upstream_connect_success_total 28843
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 29007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 43165
telemt_me_reconnect_success_total 22458
telemt_me_reader_eof_total 24403
telemt_me_idle_close_by_peer_total 24396
telemt_me_route_drop_no_conn_total 396680
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 885856
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3062
telemt_desync_full_logged_total 995
telemt_desync_suppressed_total 2067
telemt_desync_frames_bucket_total{bucket="1_2"} 814
telemt_desync_frames_bucket_total{bucket="3_10"} 1193
telemt_desync_frames_bucket_total{bucket="gt_10"} 1055
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 23408
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22446
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 950
telemt_user_connections_total{user="hello"} 883941
telemt_user_connections_current{user="hello"} 1589
telemt_user_octets_from_client{user="hello"} 46868496372 (43.65 GB)
telemt_user_octets_to_client{user="hello"} 430650305536 (401.07 GB)
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 127699.3 (35h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1553630
telemt_connections_bad_total 76098
telemt_handshake_timeouts_total 26948
telemt_upstream_connect_attempt_total 92076
telemt_upstream_connect_success_total 89625
telemt_upstream_connect_fail_total 2451
telemt_upstream_connect_attempts_per_request{bucket="1"} 92076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15212
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 382
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2451
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38942
telemt_me_reconnect_success_total 18520
telemt_me_reader_eof_total 20307
telemt_me_idle_close_by_peer_total 20304
telemt_me_route_drop_no_conn_total 624043
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1272390
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4934
telemt_desync_full_logged_total 1597
telemt_desync_suppressed_total 3337
telemt_desync_frames_bucket_total{bucket="1_2"} 1176
telemt_desync_frames_bucket_total{bucket="3_10"} 2050
telemt_desync_frames_bucket_total{bucket="gt_10"} 1708
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 19501
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18500
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 981
telemt_user_connections_total{user="hello"} 1335647
telemt_user_connections_current{user="hello"} 1916
telemt_user_octets_from_client{user="hello"} 22472630786 (20.93 GB)
telemt_user_octets_to_client{user="hello"} 652006273246 (607.23 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 127671.4 (35h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1106704
telemt_connections_bad_total 106046
telemt_handshake_timeouts_total 11010
telemt_upstream_connect_attempt_total 49003
telemt_upstream_connect_success_total 48327
telemt_upstream_connect_fail_total 676
telemt_upstream_connect_attempts_per_request{bucket="1"} 49003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 676
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60480
telemt_me_reconnect_success_total 25510
telemt_me_reader_eof_total 27588
telemt_me_idle_close_by_peer_total 27585
telemt_me_route_drop_no_conn_total 356564
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 910318
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3936
telemt_desync_full_logged_total 1212
telemt_desync_suppressed_total 2724
telemt_desync_frames_bucket_total{bucket="1_2"} 1109
telemt_desync_frames_bucket_total{bucket="3_10"} 1527
telemt_desync_frames_bucket_total{bucket="gt_10"} 1300
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26996
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25502
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1486
telemt_user_connections_total{user="hello"} 926763
telemt_user_connections_current{user="hello"} 1733
telemt_user_octets_from_client{user="hello"} 17405171572 (16.21 GB)
telemt_user_octets_to_client{user="hello"} 464607239056 (432.70 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 580
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 127833.0 (35h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1232350
telemt_connections_bad_total 128261
telemt_handshake_timeouts_total 10678
telemt_upstream_connect_attempt_total 25343
telemt_upstream_connect_success_total 25193
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 25343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12954
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 151
telemt_me_reconnect_attempts_total 30157
telemt_me_reconnect_success_total 18860
telemt_me_reader_eof_total 20428
telemt_me_idle_close_by_peer_total 20426
telemt_me_route_drop_no_conn_total 834109
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1209236
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2315
telemt_desync_full_logged_total 814
telemt_desync_suppressed_total 1501
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 885
telemt_desync_frames_bucket_total{bucket="gt_10"} 914
telemt_pool_swap_total 116
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19502
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18846
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 642
telemt_user_connections_total{user="hello"} 1017907
telemt_user_connections_current{user="hello"} 812
telemt_user_octets_from_client{user="hello"} 16155931868 (15.05 GB)
telemt_user_octets_to_client{user="hello"} 452639305444 (421.55 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 75599.5 (20h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 607328
telemt_connections_bad_total 57410
telemt_handshake_timeouts_total 13790
telemt_upstream_connect_attempt_total 25927
telemt_upstream_connect_success_total 25657
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 25927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 33385
telemt_me_reconnect_success_total 21769
telemt_me_reader_eof_total 23005
telemt_me_idle_close_by_peer_total 23005
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 150795
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 446832
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1970
telemt_desync_full_logged_total 658
telemt_desync_suppressed_total 1312
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 877
telemt_desync_frames_bucket_total{bucket="gt_10"} 766
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22365
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21724
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 446588
telemt_user_connections_current{user="hello"} 1111
telemt_user_octets_from_client{user="hello"} 26985941869 (25.13 GB)
telemt_user_octets_to_client{user="hello"} 344552096014 (320.89 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 158
```
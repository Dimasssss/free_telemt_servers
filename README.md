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

# Server Metrics 2026-03-18 05:36:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 125474.9 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1482999
telemt_connections_bad_total 10582
telemt_handshake_timeouts_total 35352
telemt_upstream_connect_attempt_total 27345
telemt_upstream_connect_success_total 26827
telemt_upstream_connect_fail_total 518
telemt_upstream_connect_attempts_per_request{bucket="1"} 27345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 518
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 35440
telemt_me_reconnect_success_total 18291
telemt_me_reader_eof_total 19837
telemt_me_idle_close_by_peer_total 19836
telemt_me_route_drop_no_conn_total 611884
telemt_me_route_drop_channel_closed_total 167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1327788
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8130
telemt_desync_full_logged_total 2445
telemt_desync_suppressed_total 5685
telemt_desync_frames_bucket_total{bucket="1_2"} 2134
telemt_desync_frames_bucket_total{bucket="3_10"} 3124
telemt_desync_frames_bucket_total{bucket="gt_10"} 2872
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 19099
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18269
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 808
telemt_user_connections_total{user="hello"} 1322017
telemt_user_connections_current{user="hello"} 890
telemt_user_octets_from_client{user="hello"} 31598781767 (29.43 GB)
telemt_user_octets_to_client{user="hello"} 473272938143 (440.77 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 125726.4 (34h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1593135
telemt_connections_bad_total 75771
telemt_handshake_timeouts_total 52486
telemt_upstream_connect_attempt_total 470776
telemt_upstream_connect_success_total 469150
telemt_upstream_connect_fail_total 1626
telemt_upstream_connect_attempts_per_request{bucket="1"} 470776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34717
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1626
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126709
telemt_me_reconnect_success_total 19980
telemt_me_reader_eof_total 22271
telemt_me_idle_close_by_peer_total 22258
telemt_me_route_drop_no_conn_total 418675
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 946030
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4223
telemt_desync_full_logged_total 1470
telemt_desync_suppressed_total 2753
telemt_desync_frames_bucket_total{bucket="1_2"} 831
telemt_desync_frames_bucket_total{bucket="3_10"} 1715
telemt_desync_frames_bucket_total{bucket="gt_10"} 1677
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 21606
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19962
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1626
telemt_user_connections_total{user="hello"} 1388380
telemt_user_connections_current{user="hello"} 1502
telemt_user_octets_from_client{user="hello"} 19170036381 (17.85 GB)
telemt_user_octets_to_client{user="hello"} 528840200754 (492.52 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 125502.5 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1061749
telemt_connections_bad_total 73132
telemt_handshake_timeouts_total 28758
telemt_upstream_connect_attempt_total 28713
telemt_upstream_connect_success_total 28551
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 28713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42960
telemt_me_reconnect_success_total 22257
telemt_me_reader_eof_total 24189
telemt_me_idle_close_by_peer_total 24182
telemt_me_route_drop_no_conn_total 378384
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 839359
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2842
telemt_desync_full_logged_total 925
telemt_desync_suppressed_total 1917
telemt_desync_frames_bucket_total{bucket="1_2"} 780
telemt_desync_frames_bucket_total{bucket="3_10"} 1105
telemt_desync_frames_bucket_total{bucket="gt_10"} 957
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 23202
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22245
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 945
telemt_user_connections_total{user="hello"} 837460
telemt_user_connections_current{user="hello"} 1341
telemt_user_octets_from_client{user="hello"} 46124837972 (42.96 GB)
telemt_user_octets_to_client{user="hello"} 403990081340 (376.25 GB)
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 125561.8 (34h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1484250
telemt_connections_bad_total 73429
telemt_handshake_timeouts_total 25620
telemt_upstream_connect_attempt_total 91715
telemt_upstream_connect_success_total 89268
telemt_upstream_connect_fail_total 2447
telemt_upstream_connect_attempts_per_request{bucket="1"} 91715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2447
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38671
telemt_me_reconnect_success_total 18253
telemt_me_reader_eof_total 20027
telemt_me_idle_close_by_peer_total 20024
telemt_me_route_drop_no_conn_total 597555
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1211158
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4683
telemt_desync_full_logged_total 1525
telemt_desync_suppressed_total 3158
telemt_desync_frames_bucket_total{bucket="1_2"} 1111
telemt_desync_frames_bucket_total{bucket="3_10"} 1954
telemt_desync_frames_bucket_total{bucket="gt_10"} 1618
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 19230
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18233
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 977
telemt_user_connections_total{user="hello"} 1274435
telemt_user_connections_current{user="hello"} 1596
telemt_user_octets_from_client{user="hello"} 20883479586 (19.45 GB)
telemt_user_octets_to_client{user="hello"} 623554604250 (580.73 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 125533.6 (34h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1043229
telemt_connections_bad_total 105520
telemt_handshake_timeouts_total 10163
telemt_upstream_connect_attempt_total 48716
telemt_upstream_connect_success_total 48044
telemt_upstream_connect_fail_total 672
telemt_upstream_connect_attempts_per_request{bucket="1"} 48716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 424
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 672
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60285
telemt_me_reconnect_success_total 25318
telemt_me_reader_eof_total 27385
telemt_me_idle_close_by_peer_total 27382
telemt_me_route_drop_no_conn_total 335541
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 854080
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
telemt_me_writer_removed_unexpected_total 26799
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25310
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1481
telemt_user_connections_total{user="hello"} 870552
telemt_user_connections_current{user="hello"} 1315
telemt_user_octets_from_client{user="hello"} 16646642780 (15.50 GB)
telemt_user_octets_to_client{user="hello"} 438690078348 (408.56 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 463
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 125694.8 (34h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1206948
telemt_connections_bad_total 127648
telemt_handshake_timeouts_total 10517
telemt_upstream_connect_attempt_total 25008
telemt_upstream_connect_success_total 24861
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 25008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29918
telemt_me_reconnect_success_total 18623
telemt_me_reader_eof_total 20177
telemt_me_idle_close_by_peer_total 20175
telemt_me_route_drop_no_conn_total 824749
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1185853
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2263
telemt_desync_full_logged_total 791
telemt_desync_suppressed_total 1472
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 860
telemt_desync_frames_bucket_total{bucket="gt_10"} 898
telemt_pool_swap_total 114
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19261
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18609
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 994534
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 15797287092 (14.71 GB)
telemt_user_octets_to_client{user="hello"} 443633694248 (413.17 GB)
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 73461.9 (20h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 563428
telemt_connections_bad_total 54623
telemt_handshake_timeouts_total 13491
telemt_upstream_connect_attempt_total 25613
telemt_upstream_connect_success_total 25347
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 25613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 33162
telemt_me_reconnect_success_total 21547
telemt_me_reader_eof_total 22770
telemt_me_idle_close_by_peer_total 22770
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 138647
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409357
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1785
telemt_desync_full_logged_total 593
telemt_desync_suppressed_total 1192
telemt_desync_frames_bucket_total{bucket="1_2"} 293
telemt_desync_frames_bucket_total{bucket="3_10"} 796
telemt_desync_frames_bucket_total{bucket="gt_10"} 696
telemt_pool_swap_total 51
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22138
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21504
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 591
telemt_user_connections_total{user="hello"} 409112
telemt_user_connections_current{user="hello"} 1071
telemt_user_octets_from_client{user="hello"} 25786764365 (24.02 GB)
telemt_user_octets_to_client{user="hello"} 321908964934 (299.80 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 120
```
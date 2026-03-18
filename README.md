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

# Server Metrics 2026-03-18 04:15:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 120590.1 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1376432
telemt_connections_bad_total 10520
telemt_handshake_timeouts_total 33765
telemt_upstream_connect_attempt_total 26528
telemt_upstream_connect_success_total 26016
telemt_upstream_connect_fail_total 512
telemt_upstream_connect_attempts_per_request{bucket="1"} 26528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 512
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34887
telemt_me_reconnect_success_total 17741
telemt_me_reader_eof_total 19246
telemt_me_idle_close_by_peer_total 19245
telemt_me_route_drop_no_conn_total 589606
telemt_me_route_drop_channel_closed_total 162
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1267737
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7953
telemt_desync_full_logged_total 2374
telemt_desync_suppressed_total 5579
telemt_desync_frames_bucket_total{bucket="1_2"} 2103
telemt_desync_frames_bucket_total{bucket="3_10"} 3045
telemt_desync_frames_bucket_total{bucket="gt_10"} 2805
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 18540
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17719
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 799
telemt_user_connections_total{user="hello"} 1261948
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 25484009191 (23.73 GB)
telemt_user_octets_to_client{user="hello"} 446612665515 (415.94 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 120841.5 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1479463
telemt_connections_bad_total 70868
telemt_handshake_timeouts_total 48309
telemt_upstream_connect_attempt_total 469924
telemt_upstream_connect_success_total 468312
telemt_upstream_connect_fail_total 1612
telemt_upstream_connect_attempts_per_request{bucket="1"} 469924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34264
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1612
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126087
telemt_me_reconnect_success_total 19361
telemt_me_reader_eof_total 21619
telemt_me_idle_close_by_peer_total 21606
telemt_me_route_drop_no_conn_total 383543
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 844727
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3823
telemt_desync_full_logged_total 1322
telemt_desync_suppressed_total 2501
telemt_desync_frames_bucket_total{bucket="1_2"} 749
telemt_desync_frames_bucket_total{bucket="3_10"} 1573
telemt_desync_frames_bucket_total{bucket="gt_10"} 1501
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 20980
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19343
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1619
telemt_user_connections_total{user="hello"} 1287046
telemt_user_connections_current{user="hello"} 1111
telemt_user_octets_from_client{user="hello"} 17428536641 (16.23 GB)
telemt_user_octets_to_client{user="hello"} 470699266030 (438.37 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 120617.4 (33h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 915680
telemt_connections_bad_total 64267
telemt_handshake_timeouts_total 26230
telemt_upstream_connect_attempt_total 27883
telemt_upstream_connect_success_total 27723
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 27883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42391
telemt_me_reconnect_success_total 21693
telemt_me_reader_eof_total 23585
telemt_me_idle_close_by_peer_total 23578
telemt_me_route_drop_no_conn_total 350537
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762235
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2409
telemt_desync_full_logged_total 787
telemt_desync_suppressed_total 1622
telemt_desync_frames_bucket_total{bucket="1_2"} 691
telemt_desync_frames_bucket_total{bucket="3_10"} 930
telemt_desync_frames_bucket_total{bucket="gt_10"} 788
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 22628
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21681
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 935
telemt_user_connections_total{user="hello"} 760348
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 44808244188 (41.73 GB)
telemt_user_octets_to_client{user="hello"} 348528570980 (324.59 GB)
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 120676.8 (33h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1379273
telemt_connections_bad_total 66103
telemt_handshake_timeouts_total 24149
telemt_upstream_connect_attempt_total 90925
telemt_upstream_connect_success_total 88490
telemt_upstream_connect_fail_total 2435
telemt_upstream_connect_attempts_per_request{bucket="1"} 90925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2435
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38123
telemt_me_reconnect_success_total 17715
telemt_me_reader_eof_total 19444
telemt_me_idle_close_by_peer_total 19441
telemt_me_route_drop_no_conn_total 561980
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1121049
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4168
telemt_desync_full_logged_total 1376
telemt_desync_suppressed_total 2792
telemt_desync_frames_bucket_total{bucket="1_2"} 1029
telemt_desync_frames_bucket_total{bucket="3_10"} 1741
telemt_desync_frames_bucket_total{bucket="gt_10"} 1398
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 18678
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17695
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 963
telemt_user_connections_total{user="hello"} 1184411
telemt_user_connections_current{user="hello"} 957
telemt_user_octets_from_client{user="hello"} 18486464758 (17.22 GB)
telemt_user_octets_to_client{user="hello"} 571347361730 (532.11 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 120648.7 (33h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 942133
telemt_connections_bad_total 102075
telemt_handshake_timeouts_total 7910
telemt_upstream_connect_attempt_total 47693
telemt_upstream_connect_success_total 47035
telemt_upstream_connect_fail_total 658
telemt_upstream_connect_attempts_per_request{bucket="1"} 47693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 420
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 658
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59526
telemt_me_reconnect_success_total 24561
telemt_me_reader_eof_total 26586
telemt_me_idle_close_by_peer_total 26583
telemt_me_route_drop_no_conn_total 300889
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 766745
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3428
telemt_desync_full_logged_total 1039
telemt_desync_suppressed_total 2389
telemt_desync_frames_bucket_total{bucket="1_2"} 1039
telemt_desync_frames_bucket_total{bucket="3_10"} 1353
telemt_desync_frames_bucket_total{bucket="gt_10"} 1036
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26035
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24553
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1474
telemt_user_connections_total{user="hello"} 783258
telemt_user_connections_current{user="hello"} 945
telemt_user_octets_from_client{user="hello"} 14910831896 (13.89 GB)
telemt_user_octets_to_client{user="hello"} 393869801536 (366.82 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 120809.9 (33h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1167080
telemt_connections_bad_total 126867
telemt_handshake_timeouts_total 10321
telemt_upstream_connect_attempt_total 24077
telemt_upstream_connect_success_total 23938
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 24077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12324
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29210
telemt_me_reconnect_success_total 17916
telemt_me_reader_eof_total 19426
telemt_me_idle_close_by_peer_total 19424
telemt_me_route_drop_no_conn_total 807521
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1147776
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2145
telemt_desync_full_logged_total 753
telemt_desync_suppressed_total 1392
telemt_desync_frames_bucket_total{bucket="1_2"} 472
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 861
telemt_pool_swap_total 109
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18546
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17902
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 957922
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 15272930592 (14.22 GB)
telemt_user_octets_to_client{user="hello"} 422168806544 (393.18 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 68576.9 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 489065
telemt_connections_bad_total 51802
telemt_handshake_timeouts_total 12622
telemt_upstream_connect_attempt_total 24611
telemt_upstream_connect_success_total 24362
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 24611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32392
telemt_me_reconnect_success_total 20780
telemt_me_reader_eof_total 21972
telemt_me_idle_close_by_peer_total 21972
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 117218
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350106
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1526
telemt_desync_full_logged_total 498
telemt_desync_suppressed_total 1028
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 685
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 47
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21367
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20737
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 587
telemt_user_connections_total{user="hello"} 349899
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 23365181173 (21.76 GB)
telemt_user_octets_to_client{user="hello"} 285430247530 (265.83 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 78
```
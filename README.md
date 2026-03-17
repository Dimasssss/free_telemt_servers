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

# Server Metrics 2026-03-17 22:49:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 101039.1 (28h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1218163
telemt_connections_bad_total 8800
telemt_handshake_timeouts_total 32225
telemt_upstream_connect_attempt_total 22808
telemt_upstream_connect_success_total 22313
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 22808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32091
telemt_me_reconnect_success_total 14959
telemt_me_reader_eof_total 16254
telemt_me_idle_close_by_peer_total 16253
telemt_me_route_drop_no_conn_total 541926
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1118052
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7364
telemt_desync_full_logged_total 2140
telemt_desync_suppressed_total 5224
telemt_desync_frames_bucket_total{bucket="1_2"} 1968
telemt_desync_frames_bucket_total{bucket="3_10"} 2783
telemt_desync_frames_bucket_total{bucket="gt_10"} 2613
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 15713
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14937
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 754
telemt_user_connections_total{user="hello"} 1112276
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 20795564663 (19.37 GB)
telemt_user_octets_to_client{user="hello"} 400692735607 (373.17 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 101290.4 (28h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1288401
telemt_connections_bad_total 60433
telemt_handshake_timeouts_total 45071
telemt_upstream_connect_attempt_total 458289
telemt_upstream_connect_success_total 457386
telemt_upstream_connect_fail_total 903
telemt_upstream_connect_attempts_per_request{bucket="1"} 458289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 903
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58482
telemt_me_reconnect_success_total 15325
telemt_me_reader_eof_total 17342
telemt_me_idle_close_by_peer_total 17342
telemt_me_route_drop_no_conn_total 334806
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680943
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3070
telemt_desync_full_logged_total 1010
telemt_desync_suppressed_total 2060
telemt_desync_frames_bucket_total{bucket="1_2"} 597
telemt_desync_frames_bucket_total{bucket="3_10"} 1260
telemt_desync_frames_bucket_total{bucket="gt_10"} 1213
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 16862
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15309
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1537
telemt_user_connections_total{user="hello"} 1117373
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 15426837762 (14.37 GB)
telemt_user_octets_to_client{user="hello"} 382439785222 (356.17 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 101066.5 (28h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 749908
telemt_connections_bad_total 46629
telemt_handshake_timeouts_total 23528
telemt_upstream_connect_attempt_total 23922
telemt_upstream_connect_success_total 23783
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 23922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12783
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39353
telemt_me_reconnect_success_total 18673
telemt_me_reader_eof_total 20360
telemt_me_idle_close_by_peer_total 20353
telemt_me_route_drop_no_conn_total 309730
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 640384
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2100
telemt_desync_full_logged_total 670
telemt_desync_suppressed_total 1430
telemt_desync_frames_bucket_total{bucket="1_2"} 588
telemt_desync_frames_bucket_total{bucket="3_10"} 815
telemt_desync_frames_bucket_total{bucket="gt_10"} 697
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 19574
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18661
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 901
telemt_user_connections_total{user="hello"} 638645
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 31156556564 (29.02 GB)
telemt_user_octets_to_client{user="hello"} 279023169072 (259.86 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 101126.0 (28h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1242591
telemt_connections_bad_total 44447
telemt_handshake_timeouts_total 21614
telemt_upstream_connect_attempt_total 83541
telemt_upstream_connect_success_total 83108
telemt_upstream_connect_fail_total 433
telemt_upstream_connect_attempts_per_request{bucket="1"} 83541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12501
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 346
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 433
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34995
telemt_me_reconnect_success_total 14672
telemt_me_reader_eof_total 16169
telemt_me_idle_close_by_peer_total 16167
telemt_me_route_drop_no_conn_total 512665
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1015991
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3817
telemt_desync_full_logged_total 1249
telemt_desync_suppressed_total 2568
telemt_desync_frames_bucket_total{bucket="1_2"} 937
telemt_desync_frames_bucket_total{bucket="3_10"} 1603
telemt_desync_frames_bucket_total{bucket="gt_10"} 1277
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 15577
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14663
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 905
telemt_user_connections_total{user="hello"} 1078480
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 16889440923 (15.73 GB)
telemt_user_octets_to_client{user="hello"} 480775212105 (447.76 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 101097.8 (28h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 800600
telemt_connections_bad_total 95069
telemt_handshake_timeouts_total 6442
telemt_upstream_connect_attempt_total 42503
telemt_upstream_connect_success_total 41926
telemt_upstream_connect_fail_total 577
telemt_upstream_connect_attempts_per_request{bucket="1"} 42503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14763
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 403
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 577
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55330
telemt_me_reconnect_success_total 20377
telemt_me_reader_eof_total 22209
telemt_me_idle_close_by_peer_total 22207
telemt_me_route_drop_no_conn_total 253755
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 641688
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2960
telemt_desync_full_logged_total 870
telemt_desync_suppressed_total 2090
telemt_desync_frames_bucket_total{bucket="1_2"} 959
telemt_desync_frames_bucket_total{bucket="3_10"} 1186
telemt_desync_frames_bucket_total{bucket="gt_10"} 815
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21815
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20369
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1438
telemt_user_connections_total{user="hello"} 658299
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 12588256128 (11.72 GB)
telemt_user_octets_to_client{user="hello"} 327295720888 (304.82 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 101258.9 (28h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1030949
telemt_connections_bad_total 86531
telemt_handshake_timeouts_total 9524
telemt_upstream_connect_attempt_total 20012
telemt_upstream_connect_success_total 19898
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 20012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26119
telemt_me_reconnect_success_total 14840
telemt_me_reader_eof_total 16112
telemt_me_idle_close_by_peer_total 16110
telemt_me_route_drop_no_conn_total 695098
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1007088
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2089
telemt_desync_full_logged_total 729
telemt_desync_suppressed_total 1360
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 792
telemt_desync_frames_bucket_total{bucket="gt_10"} 836
telemt_pool_swap_total 87
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15436
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14826
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 870115
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 13428349596 (12.51 GB)
telemt_user_octets_to_client{user="hello"} 369805572648 (344.41 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 49026.0 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363069
telemt_connections_bad_total 44502
telemt_handshake_timeouts_total 10598
telemt_upstream_connect_attempt_total 18888
telemt_upstream_connect_success_total 18712
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 18888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27686
telemt_me_reconnect_success_total 16091
telemt_me_reader_eof_total 17013
telemt_me_idle_close_by_peer_total 17013
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 90584
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 274371
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 970
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 671
telemt_desync_frames_bucket_total{bucket="1_2"} 213
telemt_desync_frames_bucket_total{bucket="3_10"} 397
telemt_desync_frames_bucket_total{bucket="gt_10"} 360
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16640
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 16062
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 549
telemt_user_connections_total{user="hello"} 274309
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 21363226269 (19.90 GB)
telemt_user_octets_to_client{user="hello"} 225519127086 (210.03 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 35
```
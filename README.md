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

# Server Metrics 2026-03-18 08:29:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 1574.7 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70562
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 721
telemt_upstream_connect_attempt_total 17232
telemt_upstream_connect_success_total 16901
telemt_upstream_connect_fail_total 331
telemt_upstream_connect_attempts_per_request{bucket="1"} 17232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 331
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 317507
telemt_me_reconnect_success_total 490
telemt_me_reader_eof_total 409
telemt_me_idle_close_by_peer_total 409
telemt_me_route_drop_no_conn_total 21042
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44980
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 29
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 178
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 403
telemt_me_refill_failed_total 9906
telemt_me_writer_restored_same_endpoint_total 487
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 14752
telemt_user_connections_total{user="hello"} 61277
telemt_user_connections_current{user="hello"} 1396
telemt_user_octets_from_client{user="hello"} 742926607 (708.51 MB)
telemt_user_octets_to_client{user="hello"} 9654026710 (8.99 GB)
telemt_user_msgs_from_client{user="hello"} 160740
telemt_user_msgs_to_client{user="hello"} 206050
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 136121.8 (37h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2122133
telemt_connections_bad_total 114910
telemt_handshake_timeouts_total 63658
telemt_upstream_connect_attempt_total 472860
telemt_upstream_connect_success_total 471196
telemt_upstream_connect_fail_total 1664
telemt_upstream_connect_attempts_per_request{bucket="1"} 472860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1664
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 137497
telemt_me_reconnect_success_total 21479
telemt_me_reader_eof_total 24085
telemt_me_idle_close_by_peer_total 24071
telemt_me_route_drop_no_conn_total 702814
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1405503
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6304
telemt_desync_full_logged_total 2187
telemt_desync_suppressed_total 4117
telemt_desync_frames_bucket_total{bucket="1_2"} 1194
telemt_desync_frames_bucket_total{bucket="3_10"} 2544
telemt_desync_frames_bucket_total{bucket="gt_10"} 2566
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 23411
telemt_me_refill_failed_total 3619
telemt_me_writer_restored_same_endpoint_total 21461
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1932
telemt_user_connections_total{user="hello"} 1847853
telemt_user_connections_current{user="hello"} 3169
telemt_user_octets_from_client{user="hello"} 31432970153 (29.27 GB)
telemt_user_octets_to_client{user="hello"} 730365002458 (680.21 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 986
telemt_user_unique_ips_recent_window{user="hello"} 400
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 135897.7 (37h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1605866
telemt_connections_bad_total 97188
telemt_handshake_timeouts_total 36500
telemt_upstream_connect_attempt_total 30562
telemt_upstream_connect_success_total 30392
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 30562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16207
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 46444
telemt_me_reconnect_success_total 23563
telemt_me_reader_eof_total 25629
telemt_me_idle_close_by_peer_total 25621
telemt_me_route_drop_no_conn_total 695384
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1184052
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4295
telemt_desync_full_logged_total 1460
telemt_desync_suppressed_total 2835
telemt_desync_frames_bucket_total{bucket="1_2"} 1169
telemt_desync_frames_bucket_total{bucket="3_10"} 1656
telemt_desync_frames_bucket_total{bucket="gt_10"} 1470
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24615
telemt_me_refill_failed_total 709
telemt_me_writer_restored_same_endpoint_total 23551
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 1052
telemt_user_connections_total{user="hello"} 1181997
telemt_user_connections_current{user="hello"} 2144
telemt_user_octets_from_client{user="hello"} 51991383904 (48.42 GB)
telemt_user_octets_to_client{user="hello"} 540177340616 (503.08 GB)
telemt_user_unique_ips_current{user="hello"} 617
telemt_user_unique_ips_recent_window{user="hello"} 286
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 135957.1 (37h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2084389
telemt_connections_bad_total 95201
telemt_handshake_timeouts_total 40055
telemt_upstream_connect_attempt_total 93769
telemt_upstream_connect_success_total 91302
telemt_upstream_connect_fail_total 2467
telemt_upstream_connect_attempts_per_request{bucket="1"} 93769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 388
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2467
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 364
telemt_me_reconnect_attempts_total 42207
telemt_me_reconnect_success_total 19741
telemt_me_reader_eof_total 21633
telemt_me_idle_close_by_peer_total 21630
telemt_me_route_drop_no_conn_total 1092844
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1741157
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6756
telemt_desync_full_logged_total 2060
telemt_desync_suppressed_total 4696
telemt_desync_frames_bucket_total{bucket="1_2"} 1500
telemt_desync_frames_bucket_total{bucket="3_10"} 2788
telemt_desync_frames_bucket_total{bucket="gt_10"} 2468
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20811
telemt_me_refill_failed_total 692
telemt_me_writer_restored_same_endpoint_total 19721
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1070
telemt_user_connections_total{user="hello"} 1804239
telemt_user_connections_current{user="hello"} 2986
telemt_user_octets_from_client{user="hello"} 29410936150 (27.39 GB)
telemt_user_octets_to_client{user="hello"} 764701194074 (712.18 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 795
telemt_user_unique_ips_recent_window{user="hello"} 401
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 135928.8 (37h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1513720
telemt_connections_bad_total 128687
telemt_handshake_timeouts_total 18783
telemt_upstream_connect_attempt_total 50218
telemt_upstream_connect_success_total 49511
telemt_upstream_connect_fail_total 707
telemt_upstream_connect_attempts_per_request{bucket="1"} 50218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 707
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 70542
telemt_me_reconnect_success_total 26286
telemt_me_reader_eof_total 28655
telemt_me_idle_close_by_peer_total 28652
telemt_me_route_drop_no_conn_total 643729
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1256526
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5442
telemt_desync_full_logged_total 1675
telemt_desync_suppressed_total 3767
telemt_desync_frames_bucket_total{bucket="1_2"} 1365
telemt_desync_frames_bucket_total{bucket="3_10"} 2093
telemt_desync_frames_bucket_total{bucket="gt_10"} 1984
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 28074
telemt_me_refill_failed_total 1377
telemt_me_writer_restored_same_endpoint_total 26278
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1788
telemt_user_connections_total{user="hello"} 1272733
telemt_user_connections_current{user="hello"} 2355
telemt_user_octets_from_client{user="hello"} 24266930132 (22.60 GB)
telemt_user_octets_to_client{user="hello"} 603246694992 (561.82 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 750
telemt_user_unique_ips_recent_window{user="hello"} 339
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 136090.0 (37h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1377664
telemt_connections_bad_total 145478
telemt_handshake_timeouts_total 11290
telemt_upstream_connect_attempt_total 27178
telemt_upstream_connect_success_total 27017
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 27178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 292
telemt_me_reconnect_attempts_total 31546
telemt_me_reconnect_success_total 20229
telemt_me_reader_eof_total 21869
telemt_me_idle_close_by_peer_total 21866
telemt_me_route_drop_no_conn_total 939129
telemt_me_route_drop_channel_closed_total 103
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1330278
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2614
telemt_desync_full_logged_total 915
telemt_desync_suppressed_total 1699
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 1009
telemt_desync_frames_bucket_total{bucket="gt_10"} 1040
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20894
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 20215
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 665
telemt_user_connections_total{user="hello"} 1138927
telemt_user_connections_current{user="hello"} 935
telemt_user_octets_from_client{user="hello"} 17240140140 (16.06 GB)
telemt_user_octets_to_client{user="hello"} 480184646404 (447.21 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 83857.0 (23h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 871388
telemt_connections_bad_total 81906
telemt_handshake_timeouts_total 18194
telemt_upstream_connect_attempt_total 27626
telemt_upstream_connect_success_total 27307
telemt_upstream_connect_fail_total 319
telemt_upstream_connect_attempts_per_request{bucket="1"} 27626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 319
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 38249
telemt_me_reconnect_success_total 22959
telemt_me_reader_eof_total 24320
telemt_me_idle_close_by_peer_total 24320
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 276986
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 665354
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2634
telemt_desync_full_logged_total 900
telemt_desync_suppressed_total 1734
telemt_desync_frames_bucket_total{bucket="1_2"} 451
telemt_desync_frames_bucket_total{bucket="3_10"} 1072
telemt_desync_frames_bucket_total{bucket="gt_10"} 1111
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23693
telemt_me_refill_failed_total 473
telemt_me_writer_restored_same_endpoint_total 22912
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 734
telemt_user_connections_total{user="hello"} 664979
telemt_user_connections_current{user="hello"} 2098
telemt_user_octets_from_client{user="hello"} 30904026473 (28.78 GB)
telemt_user_octets_to_client{user="hello"} 461181755694 (429.51 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 618
telemt_user_unique_ips_recent_window{user="hello"} 274
```
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

# Server Metrics 2026-03-18 01:01:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 108979.2 (30h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1274974
telemt_connections_bad_total 9601
telemt_handshake_timeouts_total 32474
telemt_upstream_connect_attempt_total 24376
telemt_upstream_connect_success_total 23877
telemt_upstream_connect_fail_total 499
telemt_upstream_connect_attempts_per_request{bucket="1"} 24376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 499
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33274
telemt_me_reconnect_success_total 16137
telemt_me_reader_eof_total 17519
telemt_me_idle_close_by_peer_total 17518
telemt_me_route_drop_no_conn_total 559786
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1172507
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7562
telemt_desync_full_logged_total 2220
telemt_desync_suppressed_total 5342
telemt_desync_frames_bucket_total{bucket="1_2"} 2023
telemt_desync_frames_bucket_total{bucket="3_10"} 2868
telemt_desync_frames_bucket_total{bucket="gt_10"} 2671
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 16911
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16115
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 774
telemt_user_connections_total{user="hello"} 1166720
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 22796658767 (21.23 GB)
telemt_user_octets_to_client{user="hello"} 417548132747 (388.87 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 109230.5 (30h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1352124
telemt_connections_bad_total 62260
telemt_handshake_timeouts_total 46313
telemt_upstream_connect_attempt_total 466960
telemt_upstream_connect_success_total 465411
telemt_upstream_connect_fail_total 1549
telemt_upstream_connect_attempts_per_request{bucket="1"} 466960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1549
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122463
telemt_me_reconnect_success_total 17032
telemt_me_reader_eof_total 19161
telemt_me_idle_close_by_peer_total 19151
telemt_me_route_drop_no_conn_total 349146
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 732405
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3396
telemt_desync_full_logged_total 1129
telemt_desync_suppressed_total 2267
telemt_desync_frames_bucket_total{bucket="1_2"} 667
telemt_desync_frames_bucket_total{bucket="3_10"} 1398
telemt_desync_frames_bucket_total{bucket="gt_10"} 1331
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 18580
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17014
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1548
telemt_user_connections_total{user="hello"} 1174754
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 15893031273 (14.80 GB)
telemt_user_octets_to_client{user="hello"} 402730735574 (375.07 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 109006.7 (30h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 802681
telemt_connections_bad_total 53385
telemt_handshake_timeouts_total 24182
telemt_upstream_connect_attempt_total 25581
telemt_upstream_connect_success_total 25435
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 25581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40618
telemt_me_reconnect_success_total 19933
telemt_me_reader_eof_total 21709
telemt_me_idle_close_by_peer_total 21702
telemt_me_route_drop_no_conn_total 323169
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 681440
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2170
telemt_desync_full_logged_total 706
telemt_desync_suppressed_total 1464
telemt_desync_frames_bucket_total{bucket="1_2"} 617
telemt_desync_frames_bucket_total{bucket="3_10"} 837
telemt_desync_frames_bucket_total{bucket="gt_10"} 716
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 20851
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19921
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 918
telemt_user_connections_total{user="hello"} 679574
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 36017453620 (33.54 GB)
telemt_user_octets_to_client{user="hello"} 300189894900 (279.57 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 109066.2 (30h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1287625
telemt_connections_bad_total 54253
telemt_handshake_timeouts_total 21879
telemt_upstream_connect_attempt_total 86707
telemt_upstream_connect_success_total 85284
telemt_upstream_connect_fail_total 1423
telemt_upstream_connect_attempts_per_request{bucket="1"} 86707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13343
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1423
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 36176
telemt_me_reconnect_success_total 15814
telemt_me_reader_eof_total 17447
telemt_me_idle_close_by_peer_total 17445
telemt_me_route_drop_no_conn_total 526229
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1047877
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3943
telemt_desync_full_logged_total 1305
telemt_desync_suppressed_total 2638
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 1658
telemt_desync_frames_bucket_total{bucket="gt_10"} 1319
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 16745
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15804
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 931
telemt_user_connections_total{user="hello"} 1110996
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 17444986967 (16.25 GB)
telemt_user_octets_to_client{user="hello"} 524494994318 (488.47 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 109037.9 (30h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 846151
telemt_connections_bad_total 99434
telemt_handshake_timeouts_total 6776
telemt_upstream_connect_attempt_total 44850
telemt_upstream_connect_success_total 44232
telemt_upstream_connect_fail_total 618
telemt_upstream_connect_attempts_per_request{bucket="1"} 44850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 618
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 57247
telemt_me_reconnect_success_total 22288
telemt_me_reader_eof_total 24204
telemt_me_idle_close_by_peer_total 24202
telemt_me_route_drop_no_conn_total 268802
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 681165
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3180
telemt_desync_full_logged_total 944
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 1005
telemt_desync_frames_bucket_total{bucket="3_10"} 1273
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23739
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 22280
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1451
telemt_user_connections_total{user="hello"} 697772
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 13616871264 (12.68 GB)
telemt_user_octets_to_client{user="hello"} 349091939144 (325.12 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 109198.9 (30h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1089864
telemt_connections_bad_total 107709
telemt_handshake_timeouts_total 9655
telemt_upstream_connect_attempt_total 21742
telemt_upstream_connect_success_total 21622
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 21742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27452
telemt_me_reconnect_success_total 16169
telemt_me_reader_eof_total 17551
telemt_me_idle_close_by_peer_total 17549
telemt_me_route_drop_no_conn_total 739531
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1058730
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 96
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16780
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16155
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 611
telemt_user_connections_total{user="hello"} 902419
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 14638599460 (13.63 GB)
telemt_user_octets_to_client{user="hello"} 385073067620 (358.63 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 56966.1 (15h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399925
telemt_connections_bad_total 44689
telemt_handshake_timeouts_total 10886
telemt_upstream_connect_attempt_total 21417
telemt_upstream_connect_success_total 21221
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 21417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 29808
telemt_me_reconnect_success_total 18207
telemt_me_reader_eof_total 19264
telemt_me_idle_close_by_peer_total 19264
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 99989
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294033
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1141
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 785
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 497
telemt_desync_frames_bucket_total{bucket="gt_10"} 429
telemt_pool_swap_total 36
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18775
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 18176
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 293973
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 22278636389 (20.75 GB)
telemt_user_octets_to_client{user="hello"} 243974738650 (227.22 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 25
```
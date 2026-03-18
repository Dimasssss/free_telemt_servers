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

# Server Metrics 2026-03-18 04:35:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 121811.8 (33h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1391422
telemt_connections_bad_total 10541
telemt_handshake_timeouts_total 34151
telemt_upstream_connect_attempt_total 26770
telemt_upstream_connect_success_total 26257
telemt_upstream_connect_fail_total 513
telemt_upstream_connect_attempts_per_request{bucket="1"} 26770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 513
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 35042
telemt_me_reconnect_success_total 17896
telemt_me_reader_eof_total 19414
telemt_me_idle_close_by_peer_total 19413
telemt_me_route_drop_no_conn_total 594656
telemt_me_route_drop_channel_closed_total 163
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1280558
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7974
telemt_desync_full_logged_total 2383
telemt_desync_suppressed_total 5591
telemt_desync_frames_bucket_total{bucket="1_2"} 2107
telemt_desync_frames_bucket_total{bucket="3_10"} 3054
telemt_desync_frames_bucket_total{bucket="gt_10"} 2813
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 18696
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17874
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 800
telemt_user_connections_total{user="hello"} 1274769
telemt_user_connections_current{user="hello"} 823
telemt_user_octets_from_client{user="hello"} 25650534367 (23.89 GB)
telemt_user_octets_to_client{user="hello"} 450975123239 (420.00 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 122063.2 (33h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1504257
telemt_connections_bad_total 73536
telemt_handshake_timeouts_total 49831
telemt_upstream_connect_attempt_total 470173
telemt_upstream_connect_success_total 468554
telemt_upstream_connect_fail_total 1619
telemt_upstream_connect_attempts_per_request{bucket="1"} 470173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34395
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1619
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126286
telemt_me_reconnect_success_total 19557
telemt_me_reader_eof_total 21817
telemt_me_idle_close_by_peer_total 21804
telemt_me_route_drop_no_conn_total 390790
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 865610
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3859
telemt_desync_full_logged_total 1349
telemt_desync_suppressed_total 2510
telemt_desync_frames_bucket_total{bucket="1_2"} 755
telemt_desync_frames_bucket_total{bucket="3_10"} 1584
telemt_desync_frames_bucket_total{bucket="gt_10"} 1520
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 21178
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19539
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1621
telemt_user_connections_total{user="hello"} 1307930
telemt_user_connections_current{user="hello"} 1265
telemt_user_octets_from_client{user="hello"} 17728420213 (16.51 GB)
telemt_user_octets_to_client{user="hello"} 484806839214 (451.51 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 459
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 121839.1 (33h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 941020
telemt_connections_bad_total 66579
telemt_handshake_timeouts_total 27493
telemt_upstream_connect_attempt_total 28130
telemt_upstream_connect_success_total 27970
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 28130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15037
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42552
telemt_me_reconnect_success_total 21853
telemt_me_reader_eof_total 23758
telemt_me_idle_close_by_peer_total 23751
telemt_me_route_drop_no_conn_total 355814
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 778753
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2490
telemt_desync_full_logged_total 827
telemt_desync_suppressed_total 1663
telemt_desync_frames_bucket_total{bucket="1_2"} 706
telemt_desync_frames_bucket_total{bucket="3_10"} 962
telemt_desync_frames_bucket_total{bucket="gt_10"} 822
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 22789
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21841
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 936
telemt_user_connections_total{user="hello"} 776863
telemt_user_connections_current{user="hello"} 1003
telemt_user_octets_from_client{user="hello"} 45012799564 (41.92 GB)
telemt_user_octets_to_client{user="hello"} 358814161384 (334.17 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 121898.6 (33h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1399544
telemt_connections_bad_total 68539
telemt_handshake_timeouts_total 24408
telemt_upstream_connect_attempt_total 91152
telemt_upstream_connect_success_total 88715
telemt_upstream_connect_fail_total 2437
telemt_upstream_connect_attempts_per_request{bucket="1"} 91152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2437
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38286
telemt_me_reconnect_success_total 17876
telemt_me_reader_eof_total 19623
telemt_me_idle_close_by_peer_total 19620
telemt_me_route_drop_no_conn_total 569152
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1137884
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4247
telemt_desync_full_logged_total 1397
telemt_desync_suppressed_total 2850
telemt_desync_frames_bucket_total{bucket="1_2"} 1050
telemt_desync_frames_bucket_total{bucket="3_10"} 1773
telemt_desync_frames_bucket_total{bucket="gt_10"} 1424
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 18842
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17856
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 966
telemt_user_connections_total{user="hello"} 1201190
telemt_user_connections_current{user="hello"} 1090
telemt_user_octets_from_client{user="hello"} 18725112598 (17.44 GB)
telemt_user_octets_to_client{user="hello"} 580337042046 (540.48 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 121870.5 (33h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 964340
telemt_connections_bad_total 102621
telemt_handshake_timeouts_total 8794
telemt_upstream_connect_attempt_total 48055
telemt_upstream_connect_success_total 47394
telemt_upstream_connect_fail_total 661
telemt_upstream_connect_attempts_per_request{bucket="1"} 48055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 661
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59807
telemt_me_reconnect_success_total 24841
telemt_me_reader_eof_total 26884
telemt_me_idle_close_by_peer_total 26881
telemt_me_route_drop_no_conn_total 307949
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 784725
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3515
telemt_desync_full_logged_total 1063
telemt_desync_suppressed_total 2452
telemt_desync_frames_bucket_total{bucket="1_2"} 1056
telemt_desync_frames_bucket_total{bucket="3_10"} 1379
telemt_desync_frames_bucket_total{bucket="gt_10"} 1080
telemt_pool_swap_total 64
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26317
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24833
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1476
telemt_user_connections_total{user="hello"} 801206
telemt_user_connections_current{user="hello"} 1053
telemt_user_octets_from_client{user="hello"} 15331536868 (14.28 GB)
telemt_user_octets_to_client{user="hello"} 407394270892 (379.42 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 122031.7 (33h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1175259
telemt_connections_bad_total 126940
telemt_handshake_timeouts_total 10352
telemt_upstream_connect_attempt_total 24308
telemt_upstream_connect_success_total 24169
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 24308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29398
telemt_me_reconnect_success_total 18104
telemt_me_reader_eof_total 19625
telemt_me_idle_close_by_peer_total 19623
telemt_me_route_drop_no_conn_total 812421
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1157082
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2159
telemt_desync_full_logged_total 759
telemt_desync_suppressed_total 1400
telemt_desync_frames_bucket_total{bucket="1_2"} 477
telemt_desync_frames_bucket_total{bucket="3_10"} 817
telemt_desync_frames_bucket_total{bucket="gt_10"} 865
telemt_pool_swap_total 110
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18738
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18090
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 965772
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 15388538200 (14.33 GB)
telemt_user_octets_to_client{user="hello"} 426210106356 (396.94 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 69798.8 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 507111
telemt_connections_bad_total 52833
telemt_handshake_timeouts_total 12845
telemt_upstream_connect_attempt_total 24881
telemt_upstream_connect_success_total 24627
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 24881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11362
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32614
telemt_me_reconnect_success_total 21003
telemt_me_reader_eof_total 22196
telemt_me_idle_close_by_peer_total 22196
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 121664
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362468
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1589
telemt_desync_full_logged_total 520
telemt_desync_suppressed_total 1069
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 715
telemt_desync_frames_bucket_total{bucket="gt_10"} 608
telemt_pool_swap_total 47
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21591
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20960
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 362261
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 23502070317 (21.89 GB)
telemt_user_octets_to_client{user="hello"} 293281831070 (273.14 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 84
```
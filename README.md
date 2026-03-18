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

# Server Metrics 2026-03-18 02:12:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 113258.0 (31h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1312591
telemt_connections_bad_total 9739
telemt_handshake_timeouts_total 32913
telemt_upstream_connect_attempt_total 25189
telemt_upstream_connect_success_total 24685
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 25189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33900
telemt_me_reconnect_success_total 16760
telemt_me_reader_eof_total 18194
telemt_me_idle_close_by_peer_total 18193
telemt_me_route_drop_no_conn_total 568561
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1208437
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7678
telemt_desync_full_logged_total 2273
telemt_desync_suppressed_total 5405
telemt_desync_frames_bucket_total{bucket="1_2"} 2056
telemt_desync_frames_bucket_total{bucket="3_10"} 2917
telemt_desync_frames_bucket_total{bucket="gt_10"} 2705
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 17545
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16738
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 785
telemt_user_connections_total{user="hello"} 1202651
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 24192239611 (22.53 GB)
telemt_user_octets_to_client{user="hello"} 424077107707 (394.95 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 113509.6 (31h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1385167
telemt_connections_bad_total 64215
telemt_handshake_timeouts_total 46983
telemt_upstream_connect_attempt_total 468009
telemt_upstream_connect_success_total 466432
telemt_upstream_connect_fail_total 1576
telemt_upstream_connect_attempts_per_request{bucket="1"} 468008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33241
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1576
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 123278
telemt_me_reconnect_success_total 17838
telemt_me_reader_eof_total 19996
telemt_me_idle_close_by_peer_total 19983
telemt_me_route_drop_no_conn_total 356730
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 761522
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3558
telemt_desync_full_logged_total 1209
telemt_desync_suppressed_total 2349
telemt_desync_frames_bucket_total{bucket="1_2"} 697
telemt_desync_frames_bucket_total{bucket="3_10"} 1483
telemt_desync_frames_bucket_total{bucket="gt_10"} 1378
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 19403
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17820
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1565
telemt_user_connections_total{user="hello"} 1203873
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 16280799785 (15.16 GB)
telemt_user_octets_to_client{user="hello"} 422579120070 (393.56 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 113285.4 (31h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 832571
telemt_connections_bad_total 57829
telemt_handshake_timeouts_total 24471
telemt_upstream_connect_attempt_total 26462
telemt_upstream_connect_success_total 26310
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41324
telemt_me_reconnect_success_total 20632
telemt_me_reader_eof_total 22453
telemt_me_idle_close_by_peer_total 22446
telemt_me_route_drop_no_conn_total 330727
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 702175
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2217
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1498
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 860
telemt_desync_frames_bucket_total{bucket="gt_10"} 725
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 21556
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20620
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 924
telemt_user_connections_total{user="hello"} 700293
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 43580520800 (40.59 GB)
telemt_user_octets_to_client{user="hello"} 310996311240 (289.64 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 113344.7 (31h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1313343
telemt_connections_bad_total 58340
telemt_handshake_timeouts_total 22072
telemt_upstream_connect_attempt_total 89251
telemt_upstream_connect_success_total 86840
telemt_upstream_connect_fail_total 2411
telemt_upstream_connect_attempts_per_request{bucket="1"} 89251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2411
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 36834
telemt_me_reconnect_success_total 16439
telemt_me_reader_eof_total 18113
telemt_me_idle_close_by_peer_total 18111
telemt_me_route_drop_no_conn_total 540455
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1067106
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3961
telemt_desync_full_logged_total 1314
telemt_desync_suppressed_total 2647
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 1664
telemt_desync_frames_bucket_total{bucket="gt_10"} 1329
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 17387
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16428
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 948
telemt_user_connections_total{user="hello"} 1130449
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 17728340358 (16.51 GB)
telemt_user_octets_to_client{user="hello"} 533418632386 (496.78 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 113316.6 (31h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 871123
telemt_connections_bad_total 100364
telemt_handshake_timeouts_total 6875
telemt_upstream_connect_attempt_total 46017
telemt_upstream_connect_success_total 45389
telemt_upstream_connect_fail_total 628
telemt_upstream_connect_attempts_per_request{bucket="1"} 46017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 628
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58232
telemt_me_reconnect_success_total 23270
telemt_me_reader_eof_total 25232
telemt_me_idle_close_by_peer_total 25229
telemt_me_route_drop_no_conn_total 278229
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 704459
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3228
telemt_desync_full_logged_total 966
telemt_desync_suppressed_total 2262
telemt_desync_frames_bucket_total{bucket="1_2"} 1008
telemt_desync_frames_bucket_total{bucket="3_10"} 1288
telemt_desync_frames_bucket_total{bucket="gt_10"} 932
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24736
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23262
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1466
telemt_user_connections_total{user="hello"} 721019
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 13899213612 (12.94 GB)
telemt_user_octets_to_client{user="hello"} 357047028300 (332.53 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 113477.6 (31h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1119649
telemt_connections_bad_total 119143
telemt_handshake_timeouts_total 9845
telemt_upstream_connect_attempt_total 22589
telemt_upstream_connect_success_total 22459
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 22589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28089
telemt_me_reconnect_success_total 16801
telemt_me_reader_eof_total 18216
telemt_me_idle_close_by_peer_total 18214
telemt_me_route_drop_no_conn_total 771082
telemt_me_route_drop_channel_closed_total 89
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1094422
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
telemt_pool_swap_total 100
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17419
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16787
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 919886
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 14879897856 (13.86 GB)
telemt_user_octets_to_client{user="hello"} 400266704524 (372.78 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 61244.9 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423476
telemt_connections_bad_total 44719
telemt_handshake_timeouts_total 11123
telemt_upstream_connect_attempt_total 22641
telemt_upstream_connect_success_total 22421
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 22641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30830
telemt_me_reconnect_success_total 19223
telemt_me_reader_eof_total 20316
telemt_me_idle_close_by_peer_total 20316
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 104719
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306996
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1342
telemt_desync_full_logged_total 421
telemt_desync_suppressed_total 921
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 598
telemt_desync_frames_bucket_total{bucket="gt_10"} 518
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19801
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19186
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 578
telemt_user_connections_total{user="hello"} 306932
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 22579997465 (21.03 GB)
telemt_user_octets_to_client{user="hello"} 259057198670 (241.27 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 35
```
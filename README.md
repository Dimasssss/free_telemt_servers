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

# Server Metrics 2026-03-17 19:45:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 90015.4 (25h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1114100
telemt_connections_bad_total 7966
telemt_handshake_timeouts_total 30180
telemt_upstream_connect_attempt_total 20729
telemt_upstream_connect_success_total 20241
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 20729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30578
telemt_me_reconnect_success_total 13450
telemt_me_reader_eof_total 14629
telemt_me_idle_close_by_peer_total 14628
telemt_me_route_drop_no_conn_total 501234
telemt_me_route_drop_channel_closed_total 149
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1019981
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6710
telemt_desync_full_logged_total 1926
telemt_desync_suppressed_total 4784
telemt_desync_frames_bucket_total{bucket="1_2"} 1806
telemt_desync_frames_bucket_total{bucket="3_10"} 2549
telemt_desync_frames_bucket_total{bucket="gt_10"} 2355
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 14183
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13428
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 733
telemt_user_connections_total{user="hello"} 1014220
telemt_user_connections_current{user="hello"} 915
telemt_user_octets_from_client{user="hello"} 15326508715 (14.27 GB)
telemt_user_octets_to_client{user="hello"} 354333003983 (330.00 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 90266.9 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1105165
telemt_connections_bad_total 56695
telemt_handshake_timeouts_total 38946
telemt_upstream_connect_attempt_total 456382
telemt_upstream_connect_success_total 455507
telemt_upstream_connect_fail_total 875
telemt_upstream_connect_attempts_per_request{bucket="1"} 456382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 875
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57122
telemt_me_reconnect_success_total 13971
telemt_me_reader_eof_total 15898
telemt_me_idle_close_by_peer_total 15898
telemt_me_route_drop_no_conn_total 272912
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 513104
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2099
telemt_desync_full_logged_total 669
telemt_desync_suppressed_total 1430
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 882
telemt_desync_frames_bucket_total{bucket="gt_10"} 779
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 15490
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13955
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1519
telemt_user_connections_total{user="hello"} 949541
telemt_user_connections_current{user="hello"} 1630
telemt_user_octets_from_client{user="hello"} 13244301554 (12.33 GB)
telemt_user_octets_to_client{user="hello"} 292475037126 (272.39 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 433
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 90042.9 (25h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588088
telemt_connections_bad_total 24244
telemt_handshake_timeouts_total 21975
telemt_upstream_connect_attempt_total 21948
telemt_upstream_connect_success_total 21821
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 21948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11788
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 37938
telemt_me_reconnect_success_total 17267
telemt_me_reader_eof_total 18855
telemt_me_idle_close_by_peer_total 18848
telemt_me_route_drop_no_conn_total 262069
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 513516
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1509
telemt_desync_full_logged_total 446
telemt_desync_suppressed_total 1063
telemt_desync_frames_bucket_total{bucket="1_2"} 439
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 463
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 18148
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17255
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 881
telemt_user_connections_total{user="hello"} 511814
telemt_user_connections_current{user="hello"} 1163
telemt_user_octets_from_client{user="hello"} 27661368004 (25.76 GB)
telemt_user_octets_to_client{user="hello"} 201935533488 (188.07 GB)
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 90102.3 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1087622
telemt_connections_bad_total 28023
telemt_handshake_timeouts_total 20573
telemt_upstream_connect_attempt_total 81547
telemt_upstream_connect_success_total 81142
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 81547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11455
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33540
telemt_me_reconnect_success_total 13234
telemt_me_reader_eof_total 14599
telemt_me_idle_close_by_peer_total 14598
telemt_me_route_drop_no_conn_total 449498
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 882429
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2956
telemt_desync_full_logged_total 951
telemt_desync_suppressed_total 2005
telemt_desync_frames_bucket_total{bucket="1_2"} 700
telemt_desync_frames_bucket_total{bucket="3_10"} 1286
telemt_desync_frames_bucket_total{bucket="gt_10"} 970
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 14113
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13225
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 879
telemt_user_connections_total{user="hello"} 945489
telemt_user_connections_current{user="hello"} 1374
telemt_user_octets_from_client{user="hello"} 13530752183 (12.60 GB)
telemt_user_octets_to_client{user="hello"} 363173323689 (338.23 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 90074.0 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 639916
telemt_connections_bad_total 77046
telemt_handshake_timeouts_total 5429
telemt_upstream_connect_attempt_total 40201
telemt_upstream_connect_success_total 39665
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 40201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 384
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51140
telemt_me_reconnect_success_total 18657
telemt_me_reader_eof_total 20341
telemt_me_idle_close_by_peer_total 20339
telemt_me_route_drop_no_conn_total 200139
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 505250
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2284
telemt_desync_full_logged_total 634
telemt_desync_suppressed_total 1650
telemt_desync_frames_bucket_total{bucket="1_2"} 808
telemt_desync_frames_bucket_total{bucket="3_10"} 903
telemt_desync_frames_bucket_total{bucket="gt_10"} 573
telemt_pool_swap_total 44
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19991
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18649
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1334
telemt_user_connections_total{user="hello"} 521896
telemt_user_connections_current{user="hello"} 1201
telemt_user_octets_from_client{user="hello"} 10442804516 (9.73 GB)
telemt_user_octets_to_client{user="hello"} 242092198660 (225.47 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 90236.1 (25h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 924504
telemt_connections_bad_total 61568
telemt_handshake_timeouts_total 8959
telemt_upstream_connect_attempt_total 17931
telemt_upstream_connect_success_total 17829
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 17931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9222
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24567
telemt_me_reconnect_success_total 13292
telemt_me_reader_eof_total 14451
telemt_me_idle_close_by_peer_total 14449
telemt_me_route_drop_no_conn_total 661855
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 938629
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1850
telemt_desync_full_logged_total 644
telemt_desync_suppressed_total 1206
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 696
telemt_pool_swap_total 75
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13868
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13278
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 576
telemt_user_connections_total{user="hello"} 801667
telemt_user_connections_current{user="hello"} 783
telemt_user_octets_from_client{user="hello"} 12290909912 (11.45 GB)
telemt_user_octets_to_client{user="hello"} 347392063700 (323.53 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 38002.3 (10h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253951
telemt_connections_bad_total 33274
telemt_handshake_timeouts_total 6491
telemt_upstream_connect_attempt_total 16321
telemt_upstream_connect_success_total 16171
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 16321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 25661
telemt_me_reconnect_success_total 14073
telemt_me_reader_eof_total 14882
telemt_me_idle_close_by_peer_total 14882
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 61636
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195292
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 585
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 431
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 201
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14602
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14047
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 195232
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 19127337929 (17.81 GB)
telemt_user_octets_to_client{user="hello"} 163129067458 (151.93 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 76
```
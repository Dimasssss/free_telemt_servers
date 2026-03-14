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

# Server Metrics 2026-03-14 09:04:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 178291.5 (49h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688555
telemt_connections_bad_total 32590
telemt_handshake_timeouts_total 13393
telemt_upstream_connect_attempt_total 45262
telemt_upstream_connect_success_total 45031
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 45261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5788
telemt_me_reconnect_attempts_total 40455
telemt_me_reconnect_success_total 35756
telemt_me_reader_eof_total 38227
telemt_me_idle_close_by_peer_total 38226
telemt_me_route_drop_no_conn_total 227782
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 588404
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2273
telemt_desync_full_logged_total 771
telemt_desync_suppressed_total 1502
telemt_desync_frames_bucket_total{bucket="1_2"} 491
telemt_desync_frames_bucket_total{bucket="3_10"} 829
telemt_desync_frames_bucket_total{bucket="gt_10"} 953
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 36283
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35736
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 527
telemt_user_connections_total{user="hello"} 588287
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 17088197394 (15.91 GB)
telemt_user_octets_to_client{user="hello"} 282747078700 (263.33 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 178185.5 (49h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 346667
telemt_connections_bad_total 2787
telemt_handshake_timeouts_total 3036
telemt_upstream_connect_attempt_total 152809
telemt_upstream_connect_success_total 151481
telemt_upstream_connect_fail_total 1328
telemt_upstream_connect_attempts_per_request{bucket="1"} 152809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2442
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1328
telemt_me_keepalive_timeout_total 5341
telemt_me_reconnect_attempts_total 182161
telemt_me_reconnect_success_total 39316
telemt_me_reader_eof_total 44831
telemt_me_idle_close_by_peer_total 44831
telemt_me_route_drop_no_conn_total 116576
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223997
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 44157
telemt_me_refill_failed_total 4457
telemt_me_writer_restored_same_endpoint_total 39299
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4841
telemt_user_connections_total{user="hello"} 327103
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 3396662271 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 105400036243 (98.16 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 178149.3 (49h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 403577
telemt_connections_bad_total 3199
telemt_handshake_timeouts_total 35607
telemt_upstream_connect_attempt_total 47279
telemt_upstream_connect_success_total 47270
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 47279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25556
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3552
telemt_me_reconnect_attempts_total 39663
telemt_me_reconnect_success_total 38365
telemt_me_reader_eof_total 41228
telemt_me_idle_close_by_peer_total 41228
telemt_me_route_drop_no_conn_total 145970
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350541
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 134
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 38830
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38344
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 350300
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 13705572132 (12.76 GB)
telemt_user_octets_to_client{user="hello"} 150479799824 (140.15 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 178124.7 (49h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 507561
telemt_connections_bad_total 16443
telemt_handshake_timeouts_total 4633
telemt_upstream_connect_attempt_total 77388
telemt_upstream_connect_success_total 66750
telemt_upstream_connect_fail_total 10638
telemt_upstream_connect_attempts_per_request{bucket="1"} 77388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27232
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10638
telemt_me_keepalive_timeout_total 5509
telemt_me_reconnect_attempts_total 149985
telemt_me_reconnect_success_total 38861
telemt_me_reader_eof_total 43582
telemt_me_idle_close_by_peer_total 43574
telemt_me_route_drop_no_conn_total 183905
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433707
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1923
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 1356
telemt_desync_frames_bucket_total{bucket="1_2"} 450
telemt_desync_frames_bucket_total{bucket="3_10"} 744
telemt_desync_frames_bucket_total{bucket="gt_10"} 729
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 42778
telemt_me_refill_failed_total 3465
telemt_me_writer_restored_same_endpoint_total 38851
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3917
telemt_user_connections_total{user="hello"} 452588
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 9766001627 (9.10 GB)
telemt_user_octets_to_client{user="hello"} 189170169072 (176.18 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 128296.2 (35h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211307
telemt_connections_bad_total 32473
telemt_handshake_timeouts_total 1775
telemt_upstream_connect_attempt_total 45222
telemt_upstream_connect_success_total 44785
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 45222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_timeout_total 2600
telemt_me_reconnect_attempts_total 48231
telemt_me_reconnect_success_total 33512
telemt_me_reader_eof_total 35852
telemt_me_idle_close_by_peer_total 35852
telemt_me_route_drop_no_conn_total 63618
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166437
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 718
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 34273
telemt_me_refill_failed_total 456
telemt_me_writer_restored_same_endpoint_total 33494
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 171199
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 2505646845 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 81260031803 (75.68 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 178080.9 (49h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1026678
telemt_connections_bad_total 36402
telemt_handshake_timeouts_total 26514
telemt_upstream_connect_attempt_total 37071
telemt_upstream_connect_success_total 36873
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 37071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_keepalive_timeout_total 4775
telemt_me_reconnect_attempts_total 32765
telemt_me_reconnect_success_total 28082
telemt_me_reader_eof_total 30126
telemt_me_idle_close_by_peer_total 30123
telemt_me_route_drop_no_conn_total 481964
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 951493
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 792
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 533
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 28581
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28075
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 924117
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 16911247276 (15.75 GB)
telemt_user_octets_to_client{user="hello"} 460253389892 (428.64 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 76
```
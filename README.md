# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-20 05:23:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 43555.0 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 832601
telemt_connections_bad_total 55225
telemt_connections_current 1259
telemt_connections_me_current 1259
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 19321
telemt_upstream_connect_attempt_total 8562
telemt_upstream_connect_success_total 8463
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 8562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5218
telemt_me_reconnect_success_total 5175
telemt_me_reader_eof_total 5483
telemt_me_idle_close_by_peer_total 5482
telemt_me_route_drop_no_conn_total 232119
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 668894
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3554
telemt_desync_full_logged_total 1283
telemt_desync_suppressed_total 2271
telemt_desync_frames_bucket_total{bucket="1_2"} 687
telemt_desync_frames_bucket_total{bucket="3_10"} 1393
telemt_desync_frames_bucket_total{bucket="gt_10"} 1474
telemt_pool_swap_total 48
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 5226
telemt_me_writer_restored_same_endpoint_total 5162
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 670405
telemt_user_connections_current{user="hello"} 1259
telemt_user_octets_from_client{user="hello"} 32728413668 (30.48 GB)
telemt_user_octets_to_client{user="hello"} 227994997461 (212.34 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 495
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 60010.6 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3734987
telemt_connections_bad_total 333456
telemt_connections_current 3760
telemt_connections_me_current 3760
telemt_handshake_timeouts_total 87240
telemt_upstream_connect_attempt_total 11352
telemt_upstream_connect_success_total 11145
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 11352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11194
telemt_me_reconnect_success_total 6943
telemt_me_reader_eof_total 7427
telemt_me_idle_close_by_peer_total 7427
telemt_me_route_drop_no_conn_total 1673299
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3058032
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12567
telemt_desync_full_logged_total 4204
telemt_desync_suppressed_total 8363
telemt_desync_frames_bucket_total{bucket="1_2"} 2391
telemt_desync_frames_bucket_total{bucket="3_10"} 4865
telemt_desync_frames_bucket_total{bucket="gt_10"} 5311
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 57
telemt_me_writer_removed_unexpected_total 7159
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6888
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 3057747
telemt_user_connections_current{user="hello"} 3760
telemt_user_octets_from_client{user="hello"} 46143513474 (42.97 GB)
telemt_user_octets_to_client{user="hello"} 1161737053578 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1345
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 59976.2 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3096222
telemt_connections_bad_total 228366
telemt_connections_current 2998
telemt_connections_me_current 2998
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 44098
telemt_upstream_connect_attempt_total 63701
telemt_upstream_connect_success_total 59131
telemt_upstream_connect_fail_total 4570
telemt_upstream_connect_attempts_per_request{bucket="1"} 63701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 551
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4570
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9959
telemt_me_reconnect_success_total 7016
telemt_me_reader_eof_total 7331
telemt_me_idle_close_by_peer_total 7330
telemt_me_route_drop_no_conn_total 2150340
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2520726
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9546
telemt_desync_full_logged_total 3040
telemt_desync_suppressed_total 6506
telemt_desync_frames_bucket_total{bucket="1_2"} 2271
telemt_desync_frames_bucket_total{bucket="3_10"} 3527
telemt_desync_frames_bucket_total{bucket="gt_10"} 3748
telemt_pool_swap_total 47
telemt_me_writer_close_signal_drop_total 541
telemt_me_writer_removed_unexpected_total 7706
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7012
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 690
telemt_user_connections_total{user="hello"} 2567910
telemt_user_connections_current{user="hello"} 2998
telemt_user_octets_from_client{user="hello"} 39715944117 (36.99 GB)
telemt_user_octets_to_client{user="hello"} 766312188403 (713.68 GB)
telemt_user_msgs_from_client{user="hello"} 254085
telemt_user_msgs_to_client{user="hello"} 1776413
telemt_user_unique_ips_current{user="hello"} 992
telemt_user_unique_ips_recent_window{user="hello"} 500
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 113699.4 (31h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6836480
telemt_connections_bad_total 1195655
telemt_connections_current 3388
telemt_connections_me_current 3388
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 120935
telemt_upstream_connect_attempt_total 129711
telemt_upstream_connect_success_total 96409
telemt_upstream_connect_fail_total 33302
telemt_upstream_connect_attempts_per_request{bucket="1"} 129711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33302
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 80108
telemt_me_reconnect_success_total 14428
telemt_me_reader_eof_total 15524
telemt_me_idle_close_by_peer_total 15510
telemt_me_route_drop_no_conn_total 2932517
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4826537
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20953
telemt_desync_full_logged_total 6664
telemt_desync_suppressed_total 14289
telemt_desync_frames_bucket_total{bucket="1_2"} 3719
telemt_desync_frames_bucket_total{bucket="3_10"} 8668
telemt_desync_frames_bucket_total{bucket="gt_10"} 8566
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 14757
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14403
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 4901587
telemt_user_connections_current{user="hello"} 3388
telemt_user_octets_from_client{user="hello"} 77742842804 (72.40 GB)
telemt_user_octets_to_client{user="hello"} 1938933069460 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 1160
telemt_user_unique_ips_recent_window{user="hello"} 446
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 59939.3 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1571302
telemt_connections_bad_total 103347
telemt_connections_current 1089
telemt_connections_me_current 1089
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 14381
telemt_upstream_connect_attempt_total 13771
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 473626
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1548
telemt_desync_full_logged_total 578
telemt_desync_suppressed_total 970
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1392768
telemt_user_connections_current{user="hello"} 1089
telemt_user_octets_from_client{user="hello"} 9107949151 (8.48 GB)
telemt_user_octets_to_client{user="hello"} 146631927602 (136.56 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 59940.9 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2437708
telemt_connections_bad_total 154138
telemt_connections_current 3120
telemt_connections_me_current 3120
telemt_handshake_timeouts_total 44616
telemt_upstream_connect_attempt_total 10747
telemt_upstream_connect_success_total 10680
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 10747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7748
telemt_me_reconnect_success_total 7699
telemt_me_reader_eof_total 8137
telemt_me_idle_close_by_peer_total 8137
telemt_me_route_drop_no_conn_total 855612
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2046878
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10432
telemt_desync_full_logged_total 3386
telemt_desync_suppressed_total 7046
telemt_desync_frames_bucket_total{bucket="1_2"} 2024
telemt_desync_frames_bucket_total{bucket="3_10"} 3679
telemt_desync_frames_bucket_total{bucket="gt_10"} 4729
telemt_pool_swap_total 61
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7805
telemt_me_writer_restored_same_endpoint_total 7682
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 2045575
telemt_user_connections_current{user="hello"} 3120
telemt_user_octets_from_client{user="hello"} 43800070192 (40.79 GB)
telemt_user_octets_to_client{user="hello"} 1081250223124 (1006.99 GB)
telemt_user_unique_ips_current{user="hello"} 1017
telemt_user_unique_ips_recent_window{user="hello"} 359
```
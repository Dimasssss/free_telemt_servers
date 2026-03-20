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

# Server Metrics 2026-03-20 03:00:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 34997.4 (9h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 646822
telemt_connections_bad_total 41258
telemt_connections_current 814
telemt_connections_me_current 814
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14637
telemt_upstream_connect_attempt_total 7171
telemt_upstream_connect_success_total 7081
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 7171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4268
telemt_me_reconnect_success_total 4228
telemt_me_reader_eof_total 4468
telemt_me_idle_close_by_peer_total 4467
telemt_me_route_drop_no_conn_total 182253
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 513366
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2421
telemt_desync_full_logged_total 876
telemt_desync_suppressed_total 1545
telemt_desync_frames_bucket_total{bucket="1_2"} 502
telemt_desync_frames_bucket_total{bucket="3_10"} 868
telemt_desync_frames_bucket_total{bucket="gt_10"} 1051
telemt_pool_swap_total 38
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4265
telemt_me_writer_restored_same_endpoint_total 4215
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 514799
telemt_user_connections_current{user="hello"} 814
telemt_user_octets_from_client{user="hello"} 30641943140 (28.54 GB)
telemt_user_octets_to_client{user="hello"} 177146768377 (164.98 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 51452.0 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3144572
telemt_connections_bad_total 162468
telemt_connections_current 1840
telemt_connections_me_current 1840
telemt_handshake_timeouts_total 69282
telemt_upstream_connect_attempt_total 10093
telemt_upstream_connect_success_total 9916
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 10093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10355
telemt_me_reconnect_success_total 6108
telemt_me_reader_eof_total 6538
telemt_me_idle_close_by_peer_total 6538
telemt_me_route_drop_no_conn_total 1533361
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2672774
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11443
telemt_desync_full_logged_total 3776
telemt_desync_suppressed_total 7667
telemt_desync_frames_bucket_total{bucket="1_2"} 2201
telemt_desync_frames_bucket_total{bucket="3_10"} 4469
telemt_desync_frames_bucket_total{bucket="gt_10"} 4773
telemt_pool_swap_total 45
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6310
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6053
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 2672514
telemt_user_connections_current{user="hello"} 1840
telemt_user_octets_from_client{user="hello"} 40659865846 (37.87 GB)
telemt_user_octets_to_client{user="hello"} 993765571478 (925.52 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 785
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 51430.3 (14h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3041896
telemt_connections_bad_total 479818
telemt_connections_current 1549
telemt_connections_me_current 1549
telemt_handshake_timeouts_total 48273
telemt_upstream_connect_attempt_total 8406
telemt_upstream_connect_success_total 8345
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 8406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6701
telemt_me_reconnect_success_total 5766
telemt_me_reader_eof_total 6058
telemt_me_idle_close_by_peer_total 6057
telemt_me_route_drop_no_conn_total 1944733
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2103328
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7901
telemt_desync_full_logged_total 2417
telemt_desync_suppressed_total 5484
telemt_desync_frames_bucket_total{bucket="1_2"} 1933
telemt_desync_frames_bucket_total{bucket="3_10"} 2994
telemt_desync_frames_bucket_total{bucket="gt_10"} 2974
telemt_pool_swap_total 51
telemt_me_writer_close_signal_drop_total 71
telemt_me_writer_removed_unexpected_total 5824
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5765
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 2098918
telemt_user_connections_current{user="hello"} 1549
telemt_user_octets_from_client{user="hello"} 31144336408 (29.01 GB)
telemt_user_octets_to_client{user="hello"} 811380137584 (755.66 GB)
telemt_user_unique_ips_current{user="hello"} 605
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 51418.0 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2718032
telemt_connections_bad_total 202816
telemt_connections_current 1507
telemt_connections_me_current 1507
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 32204
telemt_upstream_connect_attempt_total 56291
telemt_upstream_connect_success_total 51983
telemt_upstream_connect_fail_total 4308
telemt_upstream_connect_attempts_per_request{bucket="1"} 56291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7866
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 532
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4308
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9013
telemt_me_reconnect_success_total 6154
telemt_me_reader_eof_total 6410
telemt_me_idle_close_by_peer_total 6409
telemt_me_route_drop_no_conn_total 1883989
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2205838
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8541
telemt_desync_full_logged_total 2716
telemt_desync_suppressed_total 5825
telemt_desync_frames_bucket_total{bucket="1_2"} 2105
telemt_desync_frames_bucket_total{bucket="3_10"} 3114
telemt_desync_frames_bucket_total{bucket="gt_10"} 3322
telemt_pool_swap_total 38
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6792
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6150
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 2247923
telemt_user_connections_current{user="hello"} 1507
telemt_user_octets_from_client{user="hello"} 36337676493 (33.84 GB)
telemt_user_octets_to_client{user="hello"} 642296578613 (598.19 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 568
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 105141.4 (29h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6370416
telemt_connections_bad_total 1056605
telemt_connections_current 1555
telemt_connections_me_current 1555
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 115208
telemt_upstream_connect_attempt_total 128363
telemt_upstream_connect_success_total 95075
telemt_upstream_connect_fail_total 33288
telemt_upstream_connect_attempts_per_request{bucket="1"} 128363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1436
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33288
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79204
telemt_me_reconnect_success_total 13532
telemt_me_reader_eof_total 14567
telemt_me_idle_close_by_peer_total 14553
telemt_me_route_drop_no_conn_total 2821503
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4525648
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
telemt_desync_total 19763
telemt_desync_full_logged_total 6274
telemt_desync_suppressed_total 13489
telemt_desync_frames_bucket_total{bucket="1_2"} 3487
telemt_desync_frames_bucket_total{bucket="3_10"} 8160
telemt_desync_frames_bucket_total{bucket="gt_10"} 8116
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 13844
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13507
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 4600871
telemt_user_connections_current{user="hello"} 1555
telemt_user_octets_from_client{user="hello"} 73281687784 (68.25 GB)
telemt_user_octets_to_client{user="hello"} 1779342743120 (1.62 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 630
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 51381.2 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 943718
telemt_connections_bad_total 82843
telemt_connections_current 458
telemt_connections_me_current 458
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13292
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
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
telemt_me_route_drop_no_conn_total 472578
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
telemt_desync_total 1413
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 876
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 591
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
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
telemt_user_connections_total{user="hello"} 795265
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 7723153211 (7.19 GB)
telemt_user_octets_to_client{user="hello"} 146577719918 (136.51 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 51382.5 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2103873
telemt_connections_bad_total 124315
telemt_connections_current 1474
telemt_connections_me_current 1474
telemt_handshake_timeouts_total 39079
telemt_upstream_connect_attempt_total 9253
telemt_upstream_connect_success_total 9190
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 9253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6656
telemt_me_reconnect_success_total 6611
telemt_me_reader_eof_total 6977
telemt_me_idle_close_by_peer_total 6977
telemt_me_route_drop_no_conn_total 762963
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1795219
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9403
telemt_desync_full_logged_total 3028
telemt_desync_suppressed_total 6375
telemt_desync_frames_bucket_total{bucket="1_2"} 1791
telemt_desync_frames_bucket_total{bucket="3_10"} 3294
telemt_desync_frames_bucket_total{bucket="gt_10"} 4318
telemt_pool_swap_total 51
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6706
telemt_me_writer_restored_same_endpoint_total 6594
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 1794318
telemt_user_connections_current{user="hello"} 1474
telemt_user_octets_from_client{user="hello"} 30480895732 (28.39 GB)
telemt_user_octets_to_client{user="hello"} 918209719620 (855.15 GB)
telemt_user_unique_ips_current{user="hello"} 593
telemt_user_unique_ips_recent_window{user="hello"} 170
```
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

# Server Metrics 2026-03-19 23:57:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 23969.6 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 483647
telemt_connections_bad_total 31219
telemt_connections_current 736
telemt_connections_me_current 736
telemt_handshake_timeouts_total 7342
telemt_upstream_connect_attempt_total 4014
telemt_upstream_connect_success_total 3982
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 4014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 2795
telemt_me_reconnect_success_total 2775
telemt_me_reader_eof_total 2950
telemt_me_idle_close_by_peer_total 2949
telemt_me_route_drop_no_conn_total 142808
telemt_me_route_drop_channel_closed_total 55
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383488
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1975
telemt_desync_full_logged_total 698
telemt_desync_suppressed_total 1277
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 918
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2832
telemt_me_writer_restored_same_endpoint_total 2762
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 383761
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 29030391504 (27.04 GB)
telemt_user_octets_to_client{user="hello"} 141942594168 (132.19 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 40424.5 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2898223
telemt_connections_bad_total 123282
telemt_connections_current 1338
telemt_connections_me_current 1338
telemt_handshake_timeouts_total 60908
telemt_upstream_connect_attempt_total 8040
telemt_upstream_connect_success_total 7909
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 8040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8906
telemt_me_reconnect_success_total 4670
telemt_me_reader_eof_total 5007
telemt_me_idle_close_by_peer_total 5007
telemt_me_route_drop_no_conn_total 1474630
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2479051
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10752
telemt_desync_full_logged_total 3554
telemt_desync_suppressed_total 7198
telemt_desync_frames_bucket_total{bucket="1_2"} 2014
telemt_desync_frames_bucket_total{bucket="3_10"} 4219
telemt_desync_frames_bucket_total{bucket="gt_10"} 4519
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 4854
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4615
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 2478875
telemt_user_connections_current{user="hello"} 1338
telemt_user_octets_from_client{user="hello"} 38471182026 (35.83 GB)
telemt_user_octets_to_client{user="hello"} 896261400210 (834.71 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 618
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 40402.4 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2825640
telemt_connections_bad_total 467673
telemt_connections_current 1035
telemt_connections_me_current 1035
telemt_handshake_timeouts_total 38233
telemt_upstream_connect_attempt_total 6397
telemt_upstream_connect_success_total 6349
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 6397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5268
telemt_me_reconnect_success_total 4337
telemt_me_reader_eof_total 4533
telemt_me_idle_close_by_peer_total 4532
telemt_me_route_drop_no_conn_total 1891895
telemt_me_route_drop_channel_closed_total 170
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1963131
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7524
telemt_desync_full_logged_total 2273
telemt_desync_suppressed_total 5251
telemt_desync_frames_bucket_total{bucket="1_2"} 1852
telemt_desync_frames_bucket_total{bucket="3_10"} 2860
telemt_desync_frames_bucket_total{bucket="gt_10"} 2812
telemt_pool_swap_total 38
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 4378
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4336
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 1958888
telemt_user_connections_current{user="hello"} 1035
telemt_user_octets_from_client{user="hello"} 29335485248 (27.32 GB)
telemt_user_octets_to_client{user="hello"} 743868314008 (692.78 GB)
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 40390.4 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2462444
telemt_connections_bad_total 106621
telemt_connections_current 1086
telemt_connections_me_current 1086
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30269
telemt_upstream_connect_attempt_total 53374
telemt_upstream_connect_success_total 49208
telemt_upstream_connect_fail_total 4166
telemt_upstream_connect_attempts_per_request{bucket="1"} 53374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6917
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 520
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4166
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7639
telemt_me_reconnect_success_total 4875
telemt_me_reader_eof_total 5055
telemt_me_idle_close_by_peer_total 5054
telemt_me_route_drop_no_conn_total 1845044
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2071150
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8178
telemt_desync_full_logged_total 2578
telemt_desync_suppressed_total 5600
telemt_desync_frames_bucket_total{bucket="1_2"} 2006
telemt_desync_frames_bucket_total{bucket="3_10"} 2973
telemt_desync_frames_bucket_total{bucket="gt_10"} 3199
telemt_pool_swap_total 25
telemt_me_writer_close_signal_drop_total 403
telemt_me_writer_removed_unexpected_total 5450
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 4871
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 575
telemt_user_connections_total{user="hello"} 2112303
telemt_user_connections_current{user="hello"} 1086
telemt_user_octets_from_client{user="hello"} 34651555807 (32.27 GB)
telemt_user_octets_to_client{user="hello"} 576013276767 (536.45 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 94114.0 (26h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6170985
telemt_connections_bad_total 1038115
telemt_connections_current 1122
telemt_connections_me_current 1122
telemt_relay_adaptive_promotions_total 27
telemt_relay_adaptive_demotions_total 3535
telemt_relay_adaptive_hard_promotions_total 25
telemt_handshake_timeouts_total 111096
telemt_upstream_connect_attempt_total 117115
telemt_upstream_connect_success_total 85787
telemt_upstream_connect_fail_total 31328
telemt_upstream_connect_attempts_per_request{bucket="1"} 117115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31328
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77614
telemt_me_reconnect_success_total 12077
telemt_me_reader_eof_total 12881
telemt_me_idle_close_by_peer_total 12870
telemt_me_route_drop_no_conn_total 2771871
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4365205
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
telemt_desync_total 19200
telemt_desync_full_logged_total 6042
telemt_desync_suppressed_total 13158
telemt_desync_frames_bucket_total{bucket="1_2"} 3354
telemt_desync_frames_bucket_total{bucket="3_10"} 7883
telemt_desync_frames_bucket_total{bucket="gt_10"} 7963
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 12369
telemt_me_refill_failed_total 2043
telemt_me_writer_restored_same_endpoint_total 12052
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 4433113
telemt_user_connections_current{user="hello"} 1122
telemt_user_octets_from_client{user="hello"} 68299876602 (63.61 GB)
telemt_user_octets_to_client{user="hello"} 1714679682580 (1.56 TB)
telemt_user_msgs_from_client{user="hello"} 702760
telemt_user_msgs_to_client{user="hello"} 2862853
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 40353.6 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 679497
telemt_connections_bad_total 68947
telemt_connections_current 323
telemt_connections_me_current 323
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12849
telemt_upstream_connect_attempt_total 12277
telemt_upstream_connect_success_total 11947
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 12277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 660
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5587
telemt_me_reconnect_success_total 5482
telemt_me_reader_eof_total 5722
telemt_me_idle_close_by_peer_total 5719
telemt_me_route_drop_no_conn_total 458193
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 560417
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
telemt_desync_total 1396
telemt_desync_full_logged_total 522
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 602
telemt_pool_swap_total 34
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5531
telemt_me_writer_restored_same_endpoint_total 5473
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 548561
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 7100957167 (6.61 GB)
telemt_user_octets_to_client{user="hello"} 133341217618 (124.18 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 40355.0 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1955891
telemt_connections_bad_total 117839
telemt_connections_current 1209
telemt_connections_me_current 1209
telemt_handshake_timeouts_total 36273
telemt_upstream_connect_attempt_total 7016
telemt_upstream_connect_success_total 6963
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 7016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4980
telemt_me_reconnect_success_total 4942
telemt_me_reader_eof_total 5213
telemt_me_idle_close_by_peer_total 5213
telemt_me_route_drop_no_conn_total 724413
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1683892
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8969
telemt_desync_full_logged_total 2866
telemt_desync_suppressed_total 6103
telemt_desync_frames_bucket_total{bucket="1_2"} 1645
telemt_desync_frames_bucket_total{bucket="3_10"} 3156
telemt_desync_frames_bucket_total{bucket="gt_10"} 4168
telemt_pool_swap_total 39
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 5022
telemt_me_writer_restored_same_endpoint_total 4925
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 1683027
telemt_user_connections_current{user="hello"} 1209
telemt_user_octets_from_client{user="hello"} 28467061148 (26.51 GB)
telemt_user_octets_to_client{user="hello"} 854303346256 (795.63 GB)
telemt_user_unique_ips_current{user="hello"} 494
telemt_user_unique_ips_recent_window{user="hello"} 77
```
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

# Server Metrics 2026-03-19 23:51:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 23663.3 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480353
telemt_connections_bad_total 30776
telemt_connections_current 771
telemt_connections_me_current 771
telemt_handshake_timeouts_total 7313
telemt_upstream_connect_attempt_total 3988
telemt_upstream_connect_success_total 3956
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 3988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 2769
telemt_me_reconnect_success_total 2750
telemt_me_reader_eof_total 2923
telemt_me_idle_close_by_peer_total 2922
telemt_me_route_drop_no_conn_total 142059
telemt_me_route_drop_channel_closed_total 55
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381017
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1971
telemt_desync_full_logged_total 695
telemt_desync_suppressed_total 1276
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 645
telemt_desync_frames_bucket_total{bucket="gt_10"} 916
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2805
telemt_me_writer_restored_same_endpoint_total 2737
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 381291
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 28427849032 (26.48 GB)
telemt_user_octets_to_client{user="hello"} 141172675424 (131.48 GB)
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 40118.6 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2892692
telemt_connections_bad_total 123219
telemt_connections_current 1347
telemt_connections_me_current 1347
telemt_handshake_timeouts_total 60436
telemt_upstream_connect_attempt_total 8016
telemt_upstream_connect_success_total 7885
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 8016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8882
telemt_me_reconnect_success_total 4646
telemt_me_reader_eof_total 4981
telemt_me_idle_close_by_peer_total 4981
telemt_me_route_drop_no_conn_total 1472695
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2474129
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10749
telemt_desync_full_logged_total 3552
telemt_desync_suppressed_total 7197
telemt_desync_frames_bucket_total{bucket="1_2"} 2013
telemt_desync_frames_bucket_total{bucket="3_10"} 4218
telemt_desync_frames_bucket_total{bucket="gt_10"} 4518
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 4828
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4591
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 2473953
telemt_user_connections_current{user="hello"} 1347
telemt_user_octets_from_client{user="hello"} 38443384714 (35.80 GB)
telemt_user_octets_to_client{user="hello"} 894391900330 (832.97 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 641
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 40096.7 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2820060
telemt_connections_bad_total 467520
telemt_connections_current 1054
telemt_connections_me_current 1054
telemt_handshake_timeouts_total 38079
telemt_upstream_connect_attempt_total 6380
telemt_upstream_connect_success_total 6332
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 6380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5251
telemt_me_reconnect_success_total 4320
telemt_me_reader_eof_total 4516
telemt_me_idle_close_by_peer_total 4515
telemt_me_route_drop_no_conn_total 1890776
telemt_me_route_drop_channel_closed_total 170
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1959315
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7514
telemt_desync_full_logged_total 2271
telemt_desync_suppressed_total 5243
telemt_desync_frames_bucket_total{bucket="1_2"} 1849
telemt_desync_frames_bucket_total{bucket="3_10"} 2859
telemt_desync_frames_bucket_total{bucket="gt_10"} 2806
telemt_pool_swap_total 38
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 4361
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4319
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 1955084
telemt_user_connections_current{user="hello"} 1054
telemt_user_octets_from_client{user="hello"} 29308587748 (27.30 GB)
telemt_user_octets_to_client{user="hello"} 743021788412 (691.99 GB)
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 40084.6 (11h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2456372
telemt_connections_bad_total 104455
telemt_connections_current 997
telemt_connections_me_current 997
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30250
telemt_upstream_connect_attempt_total 53353
telemt_upstream_connect_success_total 49189
telemt_upstream_connect_fail_total 4164
telemt_upstream_connect_attempts_per_request{bucket="1"} 53353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 520
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4164
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7618
telemt_me_reconnect_success_total 4856
telemt_me_reader_eof_total 5033
telemt_me_idle_close_by_peer_total 5032
telemt_me_route_drop_no_conn_total 1843866
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2067820
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8177
telemt_desync_full_logged_total 2577
telemt_desync_suppressed_total 5600
telemt_desync_frames_bucket_total{bucket="1_2"} 2005
telemt_desync_frames_bucket_total{bucket="3_10"} 2973
telemt_desync_frames_bucket_total{bucket="gt_10"} 3199
telemt_pool_swap_total 25
telemt_me_writer_close_signal_drop_total 403
telemt_me_writer_removed_unexpected_total 5428
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 4852
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 2108976
telemt_user_connections_current{user="hello"} 997
telemt_user_octets_from_client{user="hello"} 34527382327 (32.16 GB)
telemt_user_octets_to_client{user="hello"} 574743979819 (535.27 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 93808.0 (26h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6166917
telemt_connections_bad_total 1038036
telemt_connections_current 1156
telemt_connections_me_current 1156
telemt_relay_adaptive_promotions_total 27
telemt_relay_adaptive_demotions_total 3535
telemt_relay_adaptive_hard_promotions_total 25
telemt_handshake_timeouts_total 111029
telemt_upstream_connect_attempt_total 117065
telemt_upstream_connect_success_total 85737
telemt_upstream_connect_fail_total 31328
telemt_upstream_connect_attempts_per_request{bucket="1"} 117065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31328
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77564
telemt_me_reconnect_success_total 12027
telemt_me_reader_eof_total 12829
telemt_me_idle_close_by_peer_total 12818
telemt_me_route_drop_no_conn_total 2770846
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4361372
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
telemt_desync_total 19180
telemt_desync_full_logged_total 6030
telemt_desync_suppressed_total 13150
telemt_desync_frames_bucket_total{bucket="1_2"} 3353
telemt_desync_frames_bucket_total{bucket="3_10"} 7871
telemt_desync_frames_bucket_total{bucket="gt_10"} 7956
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 12317
telemt_me_refill_failed_total 2043
telemt_me_writer_restored_same_endpoint_total 12002
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 4429281
telemt_user_connections_current{user="hello"} 1156
telemt_user_octets_from_client{user="hello"} 68283063662 (63.59 GB)
telemt_user_octets_to_client{user="hello"} 1713639680528 (1.56 TB)
telemt_user_msgs_from_client{user="hello"} 702760
telemt_user_msgs_to_client{user="hello"} 2862853
telemt_user_unique_ips_current{user="hello"} 502
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 40047.8 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 677978
telemt_connections_bad_total 68700
telemt_connections_current 297
telemt_connections_me_current 297
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12846
telemt_upstream_connect_attempt_total 12236
telemt_upstream_connect_success_total 11906
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 12236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 660
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5546
telemt_me_reconnect_success_total 5441
telemt_me_reader_eof_total 5681
telemt_me_idle_close_by_peer_total 5678
telemt_me_route_drop_no_conn_total 457648
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559176
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
telemt_me_writer_removed_unexpected_total 5490
telemt_me_writer_restored_same_endpoint_total 5432
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 547320
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 7095011359 (6.61 GB)
telemt_user_octets_to_client{user="hello"} 133253532406 (124.10 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 40049.3 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1952586
telemt_connections_bad_total 117415
telemt_connections_current 1130
telemt_connections_me_current 1130
telemt_handshake_timeouts_total 36221
telemt_upstream_connect_attempt_total 6986
telemt_upstream_connect_success_total 6933
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 6986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4950
telemt_me_reconnect_success_total 4913
telemt_me_reader_eof_total 5182
telemt_me_idle_close_by_peer_total 5182
telemt_me_route_drop_no_conn_total 723451
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1681127
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8954
telemt_desync_full_logged_total 2860
telemt_desync_suppressed_total 6094
telemt_desync_frames_bucket_total{bucket="1_2"} 1640
telemt_desync_frames_bucket_total{bucket="3_10"} 3151
telemt_desync_frames_bucket_total{bucket="gt_10"} 4163
telemt_pool_swap_total 39
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 4991
telemt_me_writer_restored_same_endpoint_total 4896
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1680262
telemt_user_connections_current{user="hello"} 1130
telemt_user_octets_from_client{user="hello"} 28431876944 (26.48 GB)
telemt_user_octets_to_client{user="hello"} 852184581964 (793.66 GB)
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 74
```
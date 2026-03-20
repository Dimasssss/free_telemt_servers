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

# Server Metrics 2026-03-20 03:51:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 38053.8 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 700522
telemt_connections_bad_total 49152
telemt_connections_current 967
telemt_connections_me_current 967
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 15310
telemt_upstream_connect_attempt_total 7710
telemt_upstream_connect_success_total 7616
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 7710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4631
telemt_me_reconnect_success_total 4591
telemt_me_reader_eof_total 4860
telemt_me_idle_close_by_peer_total 4859
telemt_me_route_drop_no_conn_total 198309
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 555647
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2694
telemt_desync_full_logged_total 985
telemt_desync_suppressed_total 1709
telemt_desync_frames_bucket_total{bucket="1_2"} 537
telemt_desync_frames_bucket_total{bucket="3_10"} 1000
telemt_desync_frames_bucket_total{bucket="gt_10"} 1157
telemt_pool_swap_total 42
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4633
telemt_me_writer_restored_same_endpoint_total 4578
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 557001
telemt_user_connections_current{user="hello"} 967
telemt_user_octets_from_client{user="hello"} 31345147792 (29.19 GB)
telemt_user_octets_to_client{user="hello"} 190291126873 (177.22 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 54509.2 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3295414
telemt_connections_bad_total 213245
telemt_connections_current 2179
telemt_connections_me_current 2179
telemt_handshake_timeouts_total 71050
telemt_upstream_connect_attempt_total 10547
telemt_upstream_connect_success_total 10359
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 10547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10669
telemt_me_reconnect_success_total 6420
telemt_me_reader_eof_total 6870
telemt_me_idle_close_by_peer_total 6870
telemt_me_route_drop_no_conn_total 1562143
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2767330
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11692
telemt_desync_full_logged_total 3867
telemt_desync_suppressed_total 7825
telemt_desync_frames_bucket_total{bucket="1_2"} 2246
telemt_desync_frames_bucket_total{bucket="3_10"} 4560
telemt_desync_frames_bucket_total{bucket="gt_10"} 4886
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6630
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6365
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 2767040
telemt_user_connections_current{user="hello"} 2179
telemt_user_octets_from_client{user="hello"} 42322987234 (39.42 GB)
telemt_user_octets_to_client{user="hello"} 1036884562918 (965.67 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 922
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 54487.7 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3124433
telemt_connections_bad_total 483149
telemt_connections_current 1803
telemt_connections_me_current 1803
telemt_handshake_timeouts_total 49804
telemt_upstream_connect_attempt_total 8915
telemt_upstream_connect_success_total 8850
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 8915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7077
telemt_me_reconnect_success_total 6140
telemt_me_reader_eof_total 6458
telemt_me_idle_close_by_peer_total 6457
telemt_me_route_drop_no_conn_total 1977870
telemt_me_route_drop_channel_closed_total 176
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2171195
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8038
telemt_desync_full_logged_total 2466
telemt_desync_suppressed_total 5572
telemt_desync_frames_bucket_total{bucket="1_2"} 1974
telemt_desync_frames_bucket_total{bucket="3_10"} 3051
telemt_desync_frames_bucket_total{bucket="gt_10"} 3013
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 73
telemt_me_writer_removed_unexpected_total 6201
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6139
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 2166220
telemt_user_connections_current{user="hello"} 1803
telemt_user_octets_from_client{user="hello"} 32873151236 (30.62 GB)
telemt_user_octets_to_client{user="hello"} 849239789660 (790.92 GB)
telemt_user_unique_ips_current{user="hello"} 703
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 54475.1 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2816300
telemt_connections_bad_total 218363
telemt_connections_current 1657
telemt_connections_me_current 1657
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 33606
telemt_upstream_connect_attempt_total 61437
telemt_upstream_connect_success_total 56939
telemt_upstream_connect_fail_total 4498
telemt_upstream_connect_attempts_per_request{bucket="1"} 61437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8320
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 550
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4498
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9413
telemt_me_reconnect_success_total 6496
telemt_me_reader_eof_total 6771
telemt_me_idle_close_by_peer_total 6770
telemt_me_route_drop_no_conn_total 1932325
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2275264
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8791
telemt_desync_full_logged_total 2808
telemt_desync_suppressed_total 5983
telemt_desync_frames_bucket_total{bucket="1_2"} 2148
telemt_desync_frames_bucket_total{bucket="3_10"} 3218
telemt_desync_frames_bucket_total{bucket="gt_10"} 3425
telemt_pool_swap_total 41
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 7172
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6492
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 676
telemt_user_connections_total{user="hello"} 2321407
telemt_user_connections_current{user="hello"} 1657
telemt_user_octets_from_client{user="hello"} 37074309722 (34.53 GB)
telemt_user_octets_to_client{user="hello"} 678459995495 (631.87 GB)
telemt_user_msgs_from_client{user="hello"} 251914
telemt_user_msgs_to_client{user="hello"} 1773933
telemt_user_unique_ips_current{user="hello"} 587
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 108198.4 (30h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6531184
telemt_connections_bad_total 1138430
telemt_connections_current 1953
telemt_connections_me_current 1953
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 116821
telemt_upstream_connect_attempt_total 128885
telemt_upstream_connect_success_total 95593
telemt_upstream_connect_fail_total 33292
telemt_upstream_connect_attempts_per_request{bucket="1"} 128885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33292
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79550
telemt_me_reconnect_success_total 13876
telemt_me_reader_eof_total 14934
telemt_me_idle_close_by_peer_total 14920
telemt_me_route_drop_no_conn_total 2849412
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4598729
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
telemt_desync_total 20028
telemt_desync_full_logged_total 6368
telemt_desync_suppressed_total 13660
telemt_desync_frames_bucket_total{bucket="1_2"} 3540
telemt_desync_frames_bucket_total{bucket="3_10"} 8279
telemt_desync_frames_bucket_total{bucket="gt_10"} 8209
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 14194
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13851
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 4673800
telemt_user_connections_current{user="hello"} 1953
telemt_user_octets_from_client{user="hello"} 74248073132 (69.15 GB)
telemt_user_octets_to_client{user="hello"} 1820371620500 (1.66 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 762
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 54438.3 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1157659
telemt_connections_bad_total 94450
telemt_connections_current 720
telemt_connections_me_current 720
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13579
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
telemt_me_route_drop_no_conn_total 473126
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
telemt_desync_total 1422
telemt_desync_full_logged_total 544
telemt_desync_suppressed_total 878
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 599
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
telemt_user_connections_total{user="hello"} 994679
telemt_user_connections_current{user="hello"} 720
telemt_user_octets_from_client{user="hello"} 8040297623 (7.49 GB)
telemt_user_octets_to_client{user="hello"} 146604679886 (136.54 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 54439.7 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2180826
telemt_connections_bad_total 132161
telemt_connections_current 2016
telemt_connections_me_current 2016
telemt_handshake_timeouts_total 41366
telemt_upstream_connect_attempt_total 9844
telemt_upstream_connect_success_total 9779
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7105
telemt_me_reconnect_success_total 7058
telemt_me_reader_eof_total 7453
telemt_me_idle_close_by_peer_total 7453
telemt_me_route_drop_no_conn_total 781322
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1853415
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9547
telemt_desync_full_logged_total 3077
telemt_desync_suppressed_total 6470
telemt_desync_frames_bucket_total{bucket="1_2"} 1854
telemt_desync_frames_bucket_total{bucket="3_10"} 3342
telemt_desync_frames_bucket_total{bucket="gt_10"} 4351
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 7156
telemt_me_writer_restored_same_endpoint_total 7041
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 1852512
telemt_user_connections_current{user="hello"} 2016
telemt_user_octets_from_client{user="hello"} 33708853460 (31.39 GB)
telemt_user_octets_to_client{user="hello"} 956729407532 (891.02 GB)
telemt_user_unique_ips_current{user="hello"} 713
telemt_user_unique_ips_recent_window{user="hello"} 193
```
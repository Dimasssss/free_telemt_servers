# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-23 02:42:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 106567.9 (29h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3650578
telemt_connections_bad_total 344573
telemt_connections_current 995
telemt_connections_me_current 995
telemt_handshake_timeouts_total 116499
telemt_upstream_connect_attempt_total 39745
telemt_upstream_connect_success_total 39744
telemt_upstream_connect_attempts_per_request{bucket="1"} 39744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25742
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1417
telemt_me_reconnect_success_total 620
telemt_me_reader_eof_total 637
telemt_me_idle_close_by_peer_total 637
telemt_me_route_drop_no_conn_total 3002408
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2990435
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 756
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 834
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 12884
telemt_desync_full_logged_total 4078
telemt_desync_suppressed_total 8806
telemt_desync_frames_bucket_total{bucket="1_2"} 3426
telemt_desync_frames_bucket_total{bucket="3_10"} 4706
telemt_desync_frames_bucket_total{bucket="gt_10"} 4752
telemt_pool_swap_total 118
telemt_pool_force_close_total 3609
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 670
telemt_me_draining_writers_reap_progress_total 36413
telemt_me_writer_removed_unexpected_total 614
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2596
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34080
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3553
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32804
telemt_me_writer_teardown_success_total{mode="normal"} 36676
telemt_me_writer_teardown_noop_total 36424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73100
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.453964
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73100
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 670
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 555
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 2979360
telemt_user_connections_current{user="hello"} 995
telemt_user_octets_from_client{user="hello"} 42537807552 (39.62 GB)
telemt_user_octets_to_client{user="hello"} 814606933868 (758.66 GB)
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 119933.6 (33h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4030384
telemt_connections_bad_total 372350
telemt_connections_current 202
telemt_connections_me_current 202
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101350
telemt_upstream_connect_attempt_total 74604
telemt_upstream_connect_success_total 73692
telemt_upstream_connect_fail_total 805
telemt_upstream_connect_attempts_per_request{bucket="1"} 74497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 805
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10410
telemt_me_reconnect_success_total 3716
telemt_me_reader_eof_total 3700
telemt_me_idle_close_by_peer_total 3700
telemt_me_route_drop_no_conn_total 3644945
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3201280
telemt_me_endpoint_quarantine_total 969
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 942
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 13048
telemt_desync_full_logged_total 7330
telemt_desync_suppressed_total 5718
telemt_desync_frames_bucket_total{bucket="1_2"} 2963
telemt_desync_frames_bucket_total{bucket="3_10"} 5123
telemt_desync_frames_bucket_total{bucket="gt_10"} 4962
telemt_pool_swap_total 113
telemt_pool_force_close_total 3180
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 49757
telemt_me_writer_removed_unexpected_total 3627
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6449
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46971
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2722
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46577
telemt_me_writer_teardown_success_total{mode="normal"} 53420
telemt_me_writer_teardown_noop_total 49758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103178
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.664119
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103178
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 3297
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 3214638
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 43305553646 (40.33 GB)
telemt_user_octets_to_client{user="hello"} 797968999038 (743.17 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 194793.5 (54h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16413700
telemt_connections_bad_total 1664900
telemt_connections_current 950
telemt_connections_me_current 950
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 399016
telemt_upstream_connect_attempt_total 87687
telemt_upstream_connect_success_total 87579
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 87596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1724
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3044
telemt_me_reconnect_success_total 1620
telemt_me_reader_eof_total 1568
telemt_me_idle_close_by_peer_total 1566
telemt_me_route_drop_no_conn_total 14056644
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13030666
telemt_me_endpoint_quarantine_total 1307
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1470
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 54076
telemt_desync_full_logged_total 17219
telemt_desync_suppressed_total 36857
telemt_desync_frames_bucket_total{bucket="1_2"} 12061
telemt_desync_frames_bucket_total{bucket="3_10"} 21121
telemt_desync_frames_bucket_total{bucket="gt_10"} 20894
telemt_pool_swap_total 211
telemt_pool_force_close_total 6855
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1069
telemt_me_draining_writers_reap_progress_total 66878
telemt_me_writer_removed_unexpected_total 1507
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5652
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62013
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6385
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60023
telemt_me_writer_teardown_success_total{mode="normal"} 67665
telemt_me_writer_teardown_noop_total 66931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134596
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.932489
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134596
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1069
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1402
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 13030651
telemt_user_connections_current{user="hello"} 950
telemt_user_octets_from_client{user="hello"} 197667090021 (184.09 GB)
telemt_user_octets_to_client{user="hello"} 3511466505383 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 194794.8 (54h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11958651
telemt_connections_bad_total 1252397
telemt_connections_current 719
telemt_connections_me_current 719
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 345280
telemt_upstream_connect_attempt_total 101973
telemt_upstream_connect_success_total 100638
telemt_upstream_connect_fail_total 882
telemt_upstream_connect_attempts_per_request{bucket="1"} 101520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 882
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4476
telemt_me_reconnect_success_total 1926
telemt_me_reader_eof_total 1792
telemt_me_idle_close_by_peer_total 1792
telemt_me_route_drop_no_conn_total 4564532
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8863021
telemt_me_endpoint_quarantine_total 1324
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1491
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 39053
telemt_desync_full_logged_total 13153
telemt_desync_suppressed_total 25900
telemt_desync_frames_bucket_total{bucket="1_2"} 9674
telemt_desync_frames_bucket_total{bucket="3_10"} 14999
telemt_desync_frames_bucket_total{bucket="gt_10"} 14380
telemt_pool_swap_total 208
telemt_pool_force_close_total 6205
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 714
telemt_me_draining_writers_reap_progress_total 65005
telemt_me_writer_removed_unexpected_total 1819
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5739
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60944
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5693
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58800
telemt_me_writer_teardown_success_total{mode="normal"} 66683
telemt_me_writer_teardown_noop_total 65030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131713
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.535036
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131713
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 714
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1649
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8800737
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 218166673180 (203.18 GB)
telemt_user_octets_to_client{user="hello"} 3977421298359 (3.62 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 194758.9 (54h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11111688
telemt_connections_bad_total 988510
telemt_connections_current 495
telemt_connections_me_current 495
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 346057
telemt_upstream_connect_attempt_total 86382
telemt_upstream_connect_success_total 84818
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 85023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5793
telemt_me_reconnect_success_total 2414
telemt_me_reader_eof_total 2159
telemt_me_idle_close_by_peer_total 2158
telemt_me_route_drop_no_conn_total 5344330
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8391904
telemt_me_endpoint_quarantine_total 1372
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1448
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 38269
telemt_desync_full_logged_total 12685
telemt_desync_suppressed_total 25584
telemt_desync_frames_bucket_total{bucket="1_2"} 9670
telemt_desync_frames_bucket_total{bucket="3_10"} 14653
telemt_desync_frames_bucket_total{bucket="gt_10"} 13946
telemt_pool_swap_total 204
telemt_pool_force_close_total 6100
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 746
telemt_me_draining_writers_reap_progress_total 65514
telemt_me_writer_removed_unexpected_total 2307
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6492
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61263
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5529
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59414
telemt_me_writer_teardown_success_total{mode="normal"} 67755
telemt_me_writer_teardown_noop_total 65585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133340
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.856438
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133340
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 746
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2101
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 8383825
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 193029533027 (179.77 GB)
telemt_user_octets_to_client{user="hello"} 3481924488961 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 65039.0 (18h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11337205
telemt_connections_bad_total 670179
telemt_connections_current 1042
telemt_connections_me_current 1042
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 285217
telemt_upstream_connect_attempt_total 60916
telemt_upstream_connect_success_total 57756
telemt_upstream_connect_fail_total 2055
telemt_upstream_connect_attempts_per_request{bucket="1"} 59811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20582
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6019
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2055
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7882
telemt_me_reconnect_success_total 1331
telemt_me_reader_eof_total 866
telemt_me_idle_close_by_peer_total 865
telemt_me_route_drop_no_conn_total 25303949
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9401299
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 521
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 16520
telemt_desync_full_logged_total 4535
telemt_desync_suppressed_total 11985
telemt_desync_frames_bucket_total{bucket="1_2"} 3146
telemt_desync_frames_bucket_total{bucket="3_10"} 6733
telemt_desync_frames_bucket_total{bucket="gt_10"} 6641
telemt_pool_swap_total 67
telemt_pool_force_close_total 2150
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 493
telemt_me_draining_writers_reap_progress_total 21239
telemt_me_writer_removed_unexpected_total 1220
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2769
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19636
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1829
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 321
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19089
telemt_me_writer_teardown_success_total{mode="normal"} 22405
telemt_me_writer_teardown_noop_total 21258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43663
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.006495
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43663
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 493
telemt_me_refill_failed_total 341
telemt_me_writer_restored_same_endpoint_total 875
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 9427142
telemt_user_connections_current{user="hello"} 1042
telemt_user_octets_from_client{user="hello"} 87760859098 (81.73 GB)
telemt_user_octets_to_client{user="hello"} 630127138114 (586.85 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 194765.5 (54h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11068571
telemt_connections_bad_total 966423
telemt_connections_current 807
telemt_connections_me_current 807
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244109
telemt_upstream_connect_attempt_total 115174
telemt_upstream_connect_success_total 113990
telemt_upstream_connect_fail_total 1009
telemt_upstream_connect_attempts_per_request{bucket="1"} 114999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44879
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1009
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73183
telemt_me_reconnect_success_total 3146
telemt_me_reader_eof_total 2843
telemt_me_idle_close_by_peer_total 2841
telemt_me_route_drop_no_conn_total 5271968
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8721602
telemt_me_endpoint_quarantine_total 1320
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1476
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 46477
telemt_desync_full_logged_total 15950
telemt_desync_suppressed_total 30527
telemt_desync_frames_bucket_total{bucket="1_2"} 9451
telemt_desync_frames_bucket_total{bucket="3_10"} 17790
telemt_desync_frames_bucket_total{bucket="gt_10"} 19236
telemt_pool_swap_total 200
telemt_pool_force_close_total 5814
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 671
telemt_me_draining_writers_reap_progress_total 69509
telemt_me_writer_removed_unexpected_total 2863
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7026
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65390
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5065
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63695
telemt_me_writer_teardown_success_total{mode="normal"} 72416
telemt_me_writer_teardown_noop_total 69510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 139772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 141190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141926
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.307452
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141926
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 671
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2649
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 8724520
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 196387056129 (182.90 GB)
telemt_user_octets_to_client{user="hello"} 3334226128684 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 131601.7 (36h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11778525
telemt_connections_bad_total 483490
telemt_connections_current 556
telemt_connections_me_current 556
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4776358
telemt_upstream_connect_attempt_total 63824
telemt_upstream_connect_success_total 63360
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 63812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_reconnect_attempts_total 49117
telemt_me_reconnect_success_total 1881
telemt_me_reader_eof_total 1560
telemt_me_idle_close_by_peer_total 1559
telemt_me_route_drop_no_conn_total 4101655
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5659478
telemt_me_endpoint_quarantine_total 903
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1012
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31831
telemt_desync_full_logged_total 10876
telemt_desync_suppressed_total 20955
telemt_desync_frames_bucket_total{bucket="1_2"} 6348
telemt_desync_frames_bucket_total{bucket="3_10"} 12563
telemt_desync_frames_bucket_total{bucket="gt_10"} 12920
telemt_pool_swap_total 140
telemt_pool_force_close_total 4020
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 381
telemt_me_draining_writers_reap_progress_total 49080
telemt_me_writer_removed_unexpected_total 1605
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3963
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46771
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3579
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45060
telemt_me_writer_teardown_success_total{mode="normal"} 50734
telemt_me_writer_teardown_noop_total 49087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99821
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.728228
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99821
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 381
telemt_me_refill_failed_total 2744
telemt_me_writer_restored_same_endpoint_total 1665
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5651583
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 120265419756 (112.01 GB)
telemt_user_octets_to_client{user="hello"} 2195222964826 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 112572.6 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1560931
telemt_connections_bad_total 36903
telemt_connections_current 460
telemt_connections_me_current 460
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32102
telemt_upstream_connect_attempt_total 53330
telemt_upstream_connect_success_total 53163
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 53302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 800
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2322
telemt_me_reconnect_success_total 952
telemt_me_reader_eof_total 942
telemt_me_idle_close_by_peer_total 942
telemt_me_route_drop_no_conn_total 525868
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1387677
telemt_me_endpoint_quarantine_total 944
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 931
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 31
telemt_desync_total 9636
telemt_desync_full_logged_total 2744
telemt_desync_suppressed_total 6892
telemt_desync_frames_bucket_total{bucket="1_2"} 2927
telemt_desync_frames_bucket_total{bucket="3_10"} 3645
telemt_desync_frames_bucket_total{bucket="gt_10"} 3064
telemt_pool_swap_total 121
telemt_pool_force_close_total 3062
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 45260
telemt_me_writer_removed_unexpected_total 907
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3435
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42774
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2974
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42198
telemt_me_writer_teardown_success_total{mode="normal"} 46209
telemt_me_writer_teardown_noop_total 45264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91473
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.413334
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91473
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 812
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1383439
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 26360690113 (24.55 GB)
telemt_user_octets_to_client{user="hello"} 585799353863 (545.57 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 194770.1 (54h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13392155
telemt_connections_bad_total 1621196
telemt_connections_current 664
telemt_connections_me_current 664
telemt_handshake_timeouts_total 391107
telemt_upstream_connect_attempt_total 77679
telemt_upstream_connect_success_total 77325
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 77543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3061
telemt_me_reconnect_success_total 1539
telemt_me_reader_eof_total 1524
telemt_me_idle_close_by_peer_total 1524
telemt_me_route_drop_no_conn_total 4489795
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10085675
telemt_me_endpoint_quarantine_total 1421
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1476
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 42299
telemt_desync_full_logged_total 13812
telemt_desync_suppressed_total 28487
telemt_desync_frames_bucket_total{bucket="1_2"} 10285
telemt_desync_frames_bucket_total{bucket="3_10"} 15538
telemt_desync_frames_bucket_total{bucket="gt_10"} 16476
telemt_pool_swap_total 216
telemt_pool_force_close_total 5694
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 684
telemt_me_draining_writers_reap_progress_total 70282
telemt_me_writer_removed_unexpected_total 1459
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5473
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66323
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5520
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64588
telemt_me_writer_teardown_success_total{mode="normal"} 71796
telemt_me_writer_teardown_noop_total 70284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 139461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 141188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142080
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.832176
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142080
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 684
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1352
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10052328
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 195076464672 (181.68 GB)
telemt_user_octets_to_client{user="hello"} 4470503062964 (4.07 TB)
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 194766.6 (54h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11698721
telemt_connections_bad_total 1367254
telemt_connections_current 707
telemt_connections_me_current 707
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 313019
telemt_upstream_connect_attempt_total 105336
telemt_upstream_connect_success_total 104430
telemt_upstream_connect_fail_total 698
telemt_upstream_connect_attempts_per_request{bucket="1"} 105128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44657
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 698
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10678
telemt_me_reconnect_success_total 2641
telemt_me_reader_eof_total 2452
telemt_me_idle_close_by_peer_total 2451
telemt_me_seq_mismatch_total 102
telemt_me_route_drop_no_conn_total 5657333
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9001141
telemt_me_endpoint_quarantine_total 1594
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1481
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 41995
telemt_desync_full_logged_total 13523
telemt_desync_suppressed_total 28472
telemt_desync_frames_bucket_total{bucket="1_2"} 10872
telemt_desync_frames_bucket_total{bucket="3_10"} 15445
telemt_desync_frames_bucket_total{bucket="gt_10"} 15678
telemt_pool_swap_total 206
telemt_pool_force_close_total 5459
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 672
telemt_me_draining_writers_reap_progress_total 70494
telemt_me_writer_removed_unexpected_total 2492
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6850
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66227
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4988
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65035
telemt_me_writer_teardown_success_total{mode="normal"} 73077
telemt_me_writer_teardown_noop_total 70499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 140885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 142668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 143207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 143526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143576
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.518012
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 672
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 2120
telemt_me_writer_restored_fallback_total 137
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 9005691
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 157668307412 (146.84 GB)
telemt_user_octets_to_client{user="hello"} 3510925831458 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 71
```
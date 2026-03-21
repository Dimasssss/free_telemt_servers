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

# Server Metrics 2026-03-21 23:42:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 9379.4 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149252
telemt_connections_bad_total 11252
telemt_connections_current 697
telemt_connections_me_current 697
telemt_handshake_timeouts_total 7457
telemt_upstream_connect_attempt_total 3795
telemt_upstream_connect_success_total 3794
telemt_upstream_connect_attempts_per_request{bucket="1"} 3794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 93
telemt_me_reconnect_success_total 59
telemt_me_reader_eof_total 60
telemt_me_idle_close_by_peer_total 60
telemt_me_route_drop_no_conn_total 31727
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121744
telemt_me_endpoint_quarantine_total 59
telemt_me_single_endpoint_shadow_rotate_total 83
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 42
telemt_desync_total 709
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 482
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 341
telemt_pool_swap_total 10
telemt_pool_force_close_total 278
telemt_me_writer_close_signal_drop_total 19
telemt_me_draining_writers_reap_progress_total 3387
telemt_me_writer_removed_unexpected_total 56
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 252
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3179
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3109
telemt_me_writer_teardown_success_total{mode="normal"} 3431
telemt_me_writer_teardown_noop_total 3387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6818
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.180775
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6818
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 19
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 121598
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 1451869416 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 45381393212 (42.26 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 22745.5 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 660869
telemt_connections_bad_total 32790
telemt_connections_current 357
telemt_connections_me_current 357
telemt_handshake_timeouts_total 25191
telemt_upstream_connect_attempt_total 9623
telemt_upstream_connect_success_total 9450
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 9605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_reconnect_attempts_total 831
telemt_me_reconnect_success_total 292
telemt_me_reader_eof_total 252
telemt_me_idle_close_by_peer_total 252
telemt_me_route_drop_no_conn_total 324830
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537934
telemt_me_endpoint_quarantine_total 204
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 2373
telemt_desync_full_logged_total 1358
telemt_desync_suppressed_total 1015
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 891
telemt_desync_frames_bucket_total{bucket="gt_10"} 977
telemt_pool_swap_total 25
telemt_pool_force_close_total 703
telemt_me_writer_close_signal_drop_total 54
telemt_me_draining_writers_reap_progress_total 8466
telemt_me_writer_removed_unexpected_total 236
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 751
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7954
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 696
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7763
telemt_me_writer_teardown_success_total{mode="normal"} 8705
telemt_me_writer_teardown_noop_total 8466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17171
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.368692
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17171
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 54
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 202
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 537191
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 9020967840 (8.40 GB)
telemt_user_octets_to_client{user="hello"} 186382465744 (173.58 GB)
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 97605.3 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7418510
telemt_connections_bad_total 586712
telemt_connections_current 1741
telemt_connections_me_current 1741
telemt_handshake_timeouts_total 240455
telemt_upstream_connect_attempt_total 35351
telemt_upstream_connect_success_total 35282
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 35289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1480
telemt_me_reconnect_success_total 734
telemt_me_reader_eof_total 742
telemt_me_idle_close_by_peer_total 742
telemt_me_route_drop_no_conn_total 4494519
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6051453
telemt_me_endpoint_quarantine_total 613
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 727
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 44
telemt_desync_total 25675
telemt_desync_full_logged_total 8478
telemt_desync_suppressed_total 17197
telemt_desync_frames_bucket_total{bucket="1_2"} 5497
telemt_desync_frames_bucket_total{bucket="3_10"} 10029
telemt_desync_frames_bucket_total{bucket="gt_10"} 10149
telemt_pool_swap_total 105
telemt_pool_force_close_total 3533
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 568
telemt_me_draining_writers_reap_progress_total 32233
telemt_me_writer_removed_unexpected_total 714
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2734
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29790
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3294
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28700
telemt_me_writer_teardown_success_total{mode="normal"} 32524
telemt_me_writer_teardown_noop_total 32277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64801
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 152.432539
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64801
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 568
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 654
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6043914
telemt_user_connections_current{user="hello"} 1741
telemt_user_octets_from_client{user="hello"} 103699760512 (96.58 GB)
telemt_user_octets_to_client{user="hello"} 1981421637640 (1.80 TB)
telemt_user_unique_ips_current{user="hello"} 799
telemt_user_unique_ips_recent_window{user="hello"} 280
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 97606.6 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6096797
telemt_connections_bad_total 577310
telemt_connections_current 1548
telemt_connections_me_current 1548
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 201570
telemt_upstream_connect_attempt_total 39279
telemt_upstream_connect_success_total 38940
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 39119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1801
telemt_me_reconnect_success_total 765
telemt_me_reader_eof_total 743
telemt_me_idle_close_by_peer_total 743
telemt_me_route_drop_no_conn_total 2162538
telemt_me_route_drop_channel_closed_total 251
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4566492
telemt_me_endpoint_quarantine_total 597
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 747
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_me_writers_active_current 44
telemt_desync_total 21993
telemt_desync_full_logged_total 7432
telemt_desync_suppressed_total 14561
telemt_desync_frames_bucket_total{bucket="1_2"} 5293
telemt_desync_frames_bucket_total{bucket="3_10"} 8535
telemt_desync_frames_bucket_total{bucket="gt_10"} 8165
telemt_pool_swap_total 107
telemt_pool_force_close_total 3224
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 30772
telemt_me_writer_removed_unexpected_total 717
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2621
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28803
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27548
telemt_me_writer_teardown_success_total{mode="normal"} 31424
telemt_me_writer_teardown_noop_total 30778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62202
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.978092
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62202
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 661
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4510094
telemt_user_connections_current{user="hello"} 1548
telemt_user_octets_from_client{user="hello"} 137719409057 (128.26 GB)
telemt_user_octets_to_client{user="hello"} 2108481599303 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 755
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 97571.8 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6011949
telemt_connections_bad_total 539380
telemt_connections_current 1561
telemt_connections_me_current 1561
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 191942
telemt_upstream_connect_attempt_total 45746
telemt_upstream_connect_success_total 45438
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 45573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20291
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1803
telemt_me_reconnect_success_total 817
telemt_me_reader_eof_total 766
telemt_me_idle_close_by_peer_total 766
telemt_me_route_drop_no_conn_total 2099798
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4490604
telemt_me_endpoint_quarantine_total 660
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 731
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_desync_total 21840
telemt_desync_full_logged_total 7262
telemt_desync_suppressed_total 14578
telemt_desync_frames_bucket_total{bucket="1_2"} 5343
telemt_desync_frames_bucket_total{bucket="3_10"} 8360
telemt_desync_frames_bucket_total{bucket="gt_10"} 8137
telemt_pool_swap_total 105
telemt_pool_force_close_total 3096
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 32254
telemt_me_writer_removed_unexpected_total 731
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2706
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30288
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2881
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29158
telemt_me_writer_teardown_success_total{mode="normal"} 32994
telemt_me_writer_teardown_noop_total 32265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65259
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.453068
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65259
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 707
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4491949
telemt_user_connections_current{user="hello"} 1561
telemt_user_octets_from_client{user="hello"} 131309255779 (122.29 GB)
telemt_user_octets_to_client{user="hello"} 2056623506643 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 754
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 97609.9 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19927842
telemt_connections_bad_total 1459088
telemt_connections_current 2196
telemt_connections_me_current 2196
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 575283
telemt_upstream_connect_attempt_total 188875
telemt_upstream_connect_success_total 171269
telemt_upstream_connect_fail_total 16031
telemt_upstream_connect_attempts_per_request{bucket="1"} 187300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39858
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8881
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16031
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64336
telemt_me_reconnect_success_total 2146
telemt_me_reader_eof_total 1341
telemt_me_idle_close_by_peer_total 1340
telemt_me_route_drop_no_conn_total 39442181
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16234044
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 750
telemt_me_single_endpoint_outage_enter_total 122
telemt_me_single_endpoint_outage_exit_total 122
telemt_me_single_endpoint_outage_reconnect_attempt_total 258
telemt_me_single_endpoint_outage_reconnect_success_total 61
telemt_me_single_endpoint_quarantine_bypass_total 258
telemt_me_single_endpoint_shadow_rotate_total 762
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
telemt_me_writers_active_current 45
telemt_desync_total 31255
telemt_desync_full_logged_total 9290
telemt_desync_suppressed_total 21965
telemt_desync_frames_bucket_total{bucket="1_2"} 6818
telemt_desync_frames_bucket_total{bucket="3_10"} 13840
telemt_desync_frames_bucket_total{bucket="gt_10"} 10597
telemt_pool_swap_total 100
telemt_pool_force_close_total 3316
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 756
telemt_me_draining_writers_reap_progress_total 30283
telemt_me_writer_removed_unexpected_total 2001
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4184
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27835
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26967
telemt_me_writer_teardown_success_total{mode="normal"} 32019
telemt_me_writer_teardown_noop_total 30309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62328
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 211.169410
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62328
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 756
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1484
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14672
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 16362008
telemt_user_connections_current{user="hello"} 2196
telemt_user_octets_from_client{user="hello"} 183868810900 (171.24 GB)
telemt_user_octets_to_client{user="hello"} 1104575595578 (1.00 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 1000
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 97577.3 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5811840
telemt_connections_bad_total 547243
telemt_connections_current 1472
telemt_connections_me_current 1472
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 119669
telemt_upstream_connect_attempt_total 53815
telemt_upstream_connect_success_total 53200
telemt_upstream_connect_fail_total 525
telemt_upstream_connect_attempts_per_request{bucket="1"} 53725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 525
telemt_me_reconnect_attempts_total 68085
telemt_me_reconnect_success_total 1678
telemt_me_reader_eof_total 1458
telemt_me_idle_close_by_peer_total 1457
telemt_me_route_drop_no_conn_total 2352773
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4529746
telemt_me_endpoint_quarantine_total 646
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 731
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 22899
telemt_desync_full_logged_total 8004
telemt_desync_suppressed_total 14895
telemt_desync_frames_bucket_total{bucket="1_2"} 4343
telemt_desync_frames_bucket_total{bucket="3_10"} 8867
telemt_desync_frames_bucket_total{bucket="gt_10"} 9689
telemt_pool_swap_total 100
telemt_pool_force_close_total 2946
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 33543
telemt_me_writer_removed_unexpected_total 1504
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3584
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31486
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2545
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30597
telemt_me_writer_teardown_success_total{mode="normal"} 35070
telemt_me_writer_teardown_noop_total 33544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68614
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.920510
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68614
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 1422
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 4522851
telemt_user_connections_current{user="hello"} 1472
telemt_user_octets_from_client{user="hello"} 121675657608 (113.32 GB)
telemt_user_octets_to_client{user="hello"} 1847773309822 (1.68 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 712
telemt_user_unique_ips_recent_window{user="hello"} 323
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 34413.2 (9h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3682375
telemt_connections_bad_total 130270
telemt_connections_current 1171
telemt_connections_me_current 1171
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1536504
telemt_upstream_connect_attempt_total 22045
telemt_upstream_connect_success_total 21905
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 22038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_reconnect_attempts_total 45582
telemt_me_reconnect_success_total 881
telemt_me_reader_eof_total 554
telemt_me_idle_close_by_peer_total 554
telemt_me_route_drop_no_conn_total 991805
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1776653
telemt_me_endpoint_quarantine_total 243
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 258
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9868
telemt_desync_full_logged_total 3376
telemt_desync_suppressed_total 6492
telemt_desync_frames_bucket_total{bucket="1_2"} 1745
telemt_desync_frames_bucket_total{bucket="3_10"} 3775
telemt_desync_frames_bucket_total{bucket="gt_10"} 4348
telemt_pool_swap_total 37
telemt_pool_force_close_total 1225
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 118
telemt_me_draining_writers_reap_progress_total 11571
telemt_me_writer_removed_unexpected_total 634
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1283
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10942
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10346
telemt_me_writer_teardown_success_total{mode="normal"} 12225
telemt_me_writer_teardown_noop_total 11573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23798
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.005679
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23798
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 118
telemt_me_refill_failed_total 2597
telemt_me_writer_restored_same_endpoint_total 792
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1780383
telemt_user_connections_current{user="hello"} 1171
telemt_user_octets_from_client{user="hello"} 52085362840 (48.51 GB)
telemt_user_octets_to_client{user="hello"} 764130786690 (711.65 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 570
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 15384.3 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155120
telemt_connections_bad_total 1394
telemt_connections_current 306
telemt_connections_me_current 306
telemt_handshake_timeouts_total 3707
telemt_upstream_connect_attempt_total 7014
telemt_upstream_connect_success_total 6996
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 7013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 138
telemt_me_reconnect_success_total 92
telemt_me_reader_eof_total 93
telemt_me_idle_close_by_peer_total 93
telemt_me_route_drop_no_conn_total 44105
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135909
telemt_me_endpoint_quarantine_total 130
telemt_me_single_endpoint_shadow_rotate_total 136
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 49
telemt_me_writers_warm_current 34
telemt_desync_total 973
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 731
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 16
telemt_pool_force_close_total 381
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 6238
telemt_me_writer_removed_unexpected_total 91
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 408
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5923
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 379
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5857
telemt_me_writer_teardown_success_total{mode="normal"} 6331
telemt_me_writer_teardown_noop_total 6238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12569
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.738957
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12569
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 135690
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 2526554716 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 79486156384 (74.03 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 97581.8 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6983008
telemt_connections_bad_total 709226
telemt_connections_current 1753
telemt_connections_me_current 1753
telemt_handshake_timeouts_total 198692
telemt_upstream_connect_attempt_total 37279
telemt_upstream_connect_success_total 37132
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 37242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 1489
telemt_me_reconnect_success_total 777
telemt_me_reader_eof_total 755
telemt_me_idle_close_by_peer_total 755
telemt_me_route_drop_no_conn_total 2092364
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5289464
telemt_me_endpoint_quarantine_total 667
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 749
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_me_writers_active_current 44
telemt_desync_total 20420
telemt_desync_full_logged_total 6805
telemt_desync_suppressed_total 13615
telemt_desync_frames_bucket_total{bucket="1_2"} 4983
telemt_desync_frames_bucket_total{bucket="3_10"} 7410
telemt_desync_frames_bucket_total{bucket="gt_10"} 8027
telemt_pool_swap_total 108
telemt_pool_force_close_total 2945
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 33547
telemt_me_writer_removed_unexpected_total 731
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2717
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31575
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30602
telemt_me_writer_teardown_success_total{mode="normal"} 34292
telemt_me_writer_teardown_noop_total 33549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67841
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.556060
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67841
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 693
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 5264685
telemt_user_connections_current{user="hello"} 1753
telemt_user_octets_from_client{user="hello"} 105809227036 (98.54 GB)
telemt_user_octets_to_client{user="hello"} 2472224902296 (2.25 TB)
telemt_user_unique_ips_current{user="hello"} 769
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 97578.2 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5987823
telemt_connections_bad_total 586340
telemt_connections_current 1832
telemt_connections_me_current 1832
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 166627
telemt_upstream_connect_attempt_total 53308
telemt_upstream_connect_success_total 52904
telemt_upstream_connect_fail_total 345
telemt_upstream_connect_attempts_per_request{bucket="1"} 53249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 345
telemt_me_reconnect_attempts_total 5294
telemt_me_reconnect_success_total 1085
telemt_me_reader_eof_total 962
telemt_me_idle_close_by_peer_total 962
telemt_me_seq_mismatch_total 41
telemt_me_route_drop_no_conn_total 2146162
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4660073
telemt_me_endpoint_quarantine_total 771
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 742
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 19177
telemt_desync_full_logged_total 6435
telemt_desync_suppressed_total 12742
telemt_desync_frames_bucket_total{bucket="1_2"} 4812
telemt_desync_frames_bucket_total{bucket="3_10"} 6978
telemt_desync_frames_bucket_total{bucket="gt_10"} 7387
telemt_pool_swap_total 106
telemt_pool_force_close_total 2908
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 365
telemt_me_draining_writers_reap_progress_total 32353
telemt_me_writer_removed_unexpected_total 974
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3195
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30176
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2685
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29445
telemt_me_writer_teardown_success_total{mode="normal"} 33371
telemt_me_writer_teardown_noop_total 32357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65728
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.858364
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65728
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 365
telemt_me_refill_failed_total 243
telemt_me_writer_restored_same_endpoint_total 841
telemt_me_writer_restored_fallback_total 54
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 4663380
telemt_user_connections_current{user="hello"} 1832
telemt_user_octets_from_client{user="hello"} 88509845845 (82.43 GB)
telemt_user_octets_to_client{user="hello"} 2003174386192 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 779
telemt_user_unique_ips_recent_window{user="hello"} 196
```
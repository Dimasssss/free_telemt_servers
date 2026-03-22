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

# Server Metrics 2026-03-22 11:22:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 51342.9 (14h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1435650
telemt_connections_bad_total 71535
telemt_connections_current 1682
telemt_connections_me_current 1682
telemt_handshake_timeouts_total 65539
telemt_upstream_connect_attempt_total 19714
telemt_upstream_connect_success_total 19713
telemt_upstream_connect_attempts_per_request{bucket="1"} 19713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12864
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 672
telemt_me_reconnect_success_total 323
telemt_me_reader_eof_total 318
telemt_me_idle_close_by_peer_total 318
telemt_me_route_drop_no_conn_total 860234
telemt_me_route_drop_channel_closed_total 432
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1207300
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 410
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 13
telemt_desync_total 7630
telemt_desync_full_logged_total 2274
telemt_desync_suppressed_total 5356
telemt_desync_frames_bucket_total{bucket="1_2"} 2194
telemt_desync_frames_bucket_total{bucket="3_10"} 2859
telemt_desync_frames_bucket_total{bucket="gt_10"} 2577
telemt_pool_swap_total 56
telemt_pool_force_close_total 1630
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 240
telemt_me_draining_writers_reap_progress_total 17926
telemt_me_writer_removed_unexpected_total 313
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1260
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16899
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1595
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16296
telemt_me_writer_teardown_success_total{mode="normal"} 18159
telemt_me_writer_teardown_noop_total 17928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36087
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 107.515355
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36087
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 240
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 289
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 1204846
telemt_user_connections_current{user="hello"} 1682
telemt_user_octets_from_client{user="hello"} 19423558344 (18.09 GB)
telemt_user_octets_to_client{user="hello"} 374025152700 (348.34 GB)
telemt_user_unique_ips_current{user="hello"} 670
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 64709.2 (17h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2332245
telemt_connections_bad_total 192960
telemt_connections_current 2269
telemt_connections_me_current 2269
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 54328
telemt_upstream_connect_attempt_total 43396
telemt_upstream_connect_success_total 42891
telemt_upstream_connect_fail_total 445
telemt_upstream_connect_attempts_per_request{bucket="1"} 43336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 445
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3325
telemt_me_reconnect_success_total 1458
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1339
telemt_me_route_drop_no_conn_total 1913773
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1836214
telemt_me_endpoint_quarantine_total 555
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 510
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 7378
telemt_desync_full_logged_total 4168
telemt_desync_suppressed_total 3210
telemt_desync_frames_bucket_total{bucket="1_2"} 1686
telemt_desync_frames_bucket_total{bucket="3_10"} 2902
telemt_desync_frames_bucket_total{bucket="gt_10"} 2790
telemt_pool_swap_total 65
telemt_pool_force_close_total 1814
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 25760
telemt_me_writer_removed_unexpected_total 1302
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2830
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24229
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1626
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23946
telemt_me_writer_teardown_success_total{mode="normal"} 27059
telemt_me_writer_teardown_noop_total 25760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52819
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.903802
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52819
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1205
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1848123
telemt_user_connections_current{user="hello"} 2269
telemt_user_octets_from_client{user="hello"} 23741541595 (22.11 GB)
telemt_user_octets_to_client{user="hello"} 473048339698 (440.56 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1356
telemt_user_unique_ips_recent_window{user="hello"} 832
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 139568.8 (38h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12106555
telemt_connections_bad_total 1041642
telemt_connections_current 5770
telemt_connections_me_current 5770
telemt_handshake_timeouts_total 319809
telemt_upstream_connect_attempt_total 50740
telemt_upstream_connect_success_total 50660
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 50668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27540
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2170
telemt_me_reconnect_success_total 1113
telemt_me_reader_eof_total 1094
telemt_me_idle_close_by_peer_total 1093
telemt_me_route_drop_no_conn_total 9535185
telemt_me_route_drop_channel_closed_total 105
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9665143
telemt_me_endpoint_quarantine_total 886
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1037
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 21
telemt_desync_total 39618
telemt_desync_full_logged_total 12743
telemt_desync_suppressed_total 26875
telemt_desync_frames_bucket_total{bucket="1_2"} 8925
telemt_desync_frames_bucket_total{bucket="3_10"} 15447
telemt_desync_frames_bucket_total{bucket="gt_10"} 15246
telemt_pool_swap_total 150
telemt_pool_force_close_total 5043
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 786
telemt_me_draining_writers_reap_progress_total 46251
telemt_me_writer_removed_unexpected_total 1054
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3964
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42753
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4709
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41208
telemt_me_writer_teardown_success_total{mode="normal"} 46717
telemt_me_writer_teardown_noop_total 46295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93012
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.348006
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93012
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 786
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 969
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 9654228
telemt_user_connections_current{user="hello"} 5770
telemt_user_octets_from_client{user="hello"} 145048445584 (135.09 GB)
telemt_user_octets_to_client{user="hello"} 2760682297952 (2.51 TB)
telemt_user_unique_ips_current{user="hello"} 2192
telemt_user_unique_ips_recent_window{user="hello"} 903
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 139570.4 (38h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9183204
telemt_connections_bad_total 823154
telemt_connections_current 4040
telemt_connections_me_current 4040
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 280115
telemt_upstream_connect_attempt_total 57382
telemt_upstream_connect_success_total 56804
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 57068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27917
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3192
telemt_me_reconnect_success_total 1300
telemt_me_reader_eof_total 1192
telemt_me_idle_close_by_peer_total 1192
telemt_me_route_drop_no_conn_total 3727757
telemt_me_route_drop_channel_closed_total 382
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6847797
telemt_me_endpoint_quarantine_total 881
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 1066
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_warm_current 19
telemt_desync_total 31088
telemt_desync_full_logged_total 10497
telemt_desync_suppressed_total 20591
telemt_desync_frames_bucket_total{bucket="1_2"} 7643
telemt_desync_frames_bucket_total{bucket="3_10"} 11971
telemt_desync_frames_bucket_total{bucket="gt_10"} 11474
telemt_pool_swap_total 149
telemt_pool_force_close_total 4570
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 522
telemt_me_draining_writers_reap_progress_total 44848
telemt_me_writer_removed_unexpected_total 1225
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3947
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42022
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40278
telemt_me_writer_teardown_success_total{mode="normal"} 45969
telemt_me_writer_teardown_noop_total 44856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90825
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 69.541353
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90825
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 522
telemt_me_refill_failed_total 103
telemt_me_writer_restored_same_endpoint_total 1116
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6769304
telemt_user_connections_current{user="hello"} 4040
telemt_user_octets_from_client{user="hello"} 177074601327 (164.91 GB)
telemt_user_octets_to_client{user="hello"} 3116876246862 (2.83 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1698
telemt_user_unique_ips_recent_window{user="hello"} 604
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 139534.4 (38h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8712764
telemt_connections_bad_total 724103
telemt_connections_current 3980
telemt_connections_me_current 3980
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 278698
telemt_upstream_connect_attempt_total 61585
telemt_upstream_connect_success_total 60872
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 61019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28731
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1395
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3726
telemt_me_reconnect_success_total 1541
telemt_me_reader_eof_total 1429
telemt_me_idle_close_by_peer_total 1429
telemt_me_route_drop_no_conn_total 3692184
telemt_me_route_drop_channel_closed_total 250
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6549765
telemt_me_endpoint_quarantine_total 954
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1020
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_me_writers_active_current 84
telemt_me_writers_warm_current 9
telemt_desync_total 30278
telemt_desync_full_logged_total 10295
telemt_desync_suppressed_total 19983
telemt_desync_frames_bucket_total{bucket="1_2"} 7361
telemt_desync_frames_bucket_total{bucket="3_10"} 11688
telemt_desync_frames_bucket_total{bucket="gt_10"} 11229
telemt_pool_swap_total 146
telemt_pool_force_close_total 4462
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 531
telemt_me_draining_writers_reap_progress_total 45510
telemt_me_writer_removed_unexpected_total 1456
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4317
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42587
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41048
telemt_me_writer_teardown_success_total{mode="normal"} 46904
telemt_me_writer_teardown_noop_total 45527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92431
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 56.101130
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92431
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 531
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1360
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6541143
telemt_user_connections_current{user="hello"} 3980
telemt_user_octets_from_client{user="hello"} 161216993759 (150.15 GB)
telemt_user_octets_to_client{user="hello"} 2840059611451 (2.58 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1746
telemt_user_unique_ips_recent_window{user="hello"} 498
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 9814.3 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4171693
telemt_connections_bad_total 268569
telemt_connections_current 6703
telemt_connections_me_current 6703
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 63575
telemt_upstream_connect_attempt_total 22869
telemt_upstream_connect_success_total 21839
telemt_upstream_connect_fail_total 829
telemt_upstream_connect_attempts_per_request{bucket="1"} 22668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4260
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4612
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 829
telemt_me_keepalive_timeout_total 415
telemt_me_reconnect_attempts_total 705
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 192
telemt_me_idle_close_by_peer_total 192
telemt_me_route_drop_no_conn_total 9520270
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3476989
telemt_me_endpoint_quarantine_total 69
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 5107
telemt_desync_full_logged_total 1336
telemt_desync_suppressed_total 3771
telemt_desync_frames_bucket_total{bucket="1_2"} 943
telemt_desync_frames_bucket_total{bucket="3_10"} 2033
telemt_desync_frames_bucket_total{bucket="gt_10"} 2131
telemt_pool_swap_total 8
telemt_pool_force_close_total 366
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 2551
telemt_me_writer_removed_unexpected_total 281
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 485
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2310
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 243
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 123
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2185
telemt_me_writer_teardown_success_total{mode="normal"} 2795
telemt_me_writer_teardown_noop_total 2554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5349
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.483231
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5349
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 206
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 58
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 3492445
telemt_user_connections_current{user="hello"} 6703
telemt_user_octets_from_client{user="hello"} 18973046202 (17.67 GB)
telemt_user_octets_to_client{user="hello"} 102640956803 (95.59 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2392
telemt_user_unique_ips_recent_window{user="hello"} 1316
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 139541.1 (38h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8446857
telemt_connections_bad_total 735195
telemt_connections_current 5008
telemt_connections_me_current 5008
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 175370
telemt_upstream_connect_attempt_total 86822
telemt_upstream_connect_success_total 85964
telemt_upstream_connect_fail_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 86702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 738
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70678
telemt_me_reconnect_success_total 2187
telemt_me_reader_eof_total 1924
telemt_me_idle_close_by_peer_total 1923
telemt_me_route_drop_no_conn_total 3777381
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6668009
telemt_me_endpoint_quarantine_total 933
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1046
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_warm_current 9
telemt_desync_total 34029
telemt_desync_full_logged_total 11716
telemt_desync_suppressed_total 22313
telemt_desync_frames_bucket_total{bucket="1_2"} 6985
telemt_desync_frames_bucket_total{bucket="3_10"} 13067
telemt_desync_frames_bucket_total{bucket="gt_10"} 13977
telemt_pool_swap_total 144
telemt_pool_force_close_total 4191
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 505
telemt_me_draining_writers_reap_progress_total 47935
telemt_me_writer_removed_unexpected_total 1953
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4936
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44977
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3651
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 540
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43744
telemt_me_writer_teardown_success_total{mode="normal"} 49913
telemt_me_writer_teardown_noop_total 47936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97849
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.746056
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97849
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 505
telemt_me_refill_failed_total 4235
telemt_me_writer_restored_same_endpoint_total 1818
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6671204
telemt_user_connections_current{user="hello"} 5008
telemt_user_octets_from_client{user="hello"} 159286361811 (148.35 GB)
telemt_user_octets_to_client{user="hello"} 2621494320413 (2.38 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1967
telemt_user_unique_ips_recent_window{user="hello"} 666
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 76377.2 (21h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7655132
telemt_connections_bad_total 281992
telemt_connections_current 4313
telemt_connections_me_current 4313
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3173101
telemt_upstream_connect_attempt_total 39325
telemt_upstream_connect_success_total 39039
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 39318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_reconnect_attempts_total 47703
telemt_me_reconnect_success_total 1341
telemt_me_reader_eof_total 1004
telemt_me_idle_close_by_peer_total 1004
telemt_me_route_drop_no_conn_total 2449497
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3758079
telemt_me_endpoint_quarantine_total 516
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 579
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 20448
telemt_desync_full_logged_total 6849
telemt_desync_suppressed_total 13599
telemt_desync_frames_bucket_total{bucket="1_2"} 4149
telemt_desync_frames_bucket_total{bucket="3_10"} 7909
telemt_desync_frames_bucket_total{bucket="gt_10"} 8390
telemt_pool_swap_total 80
telemt_pool_force_close_total 2456
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 27035
telemt_me_writer_removed_unexpected_total 1072
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2408
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25724
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2098
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 358
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24579
telemt_me_writer_teardown_success_total{mode="normal"} 28132
telemt_me_writer_teardown_noop_total 27042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55174
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.389937
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55174
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 2695
telemt_me_writer_restored_same_endpoint_total 1194
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3756421
telemt_user_connections_current{user="hello"} 4313
telemt_user_octets_from_client{user="hello"} 87771819028 (81.74 GB)
telemt_user_octets_to_client{user="hello"} 1512669335638 (1.38 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1690
telemt_user_unique_ips_recent_window{user="hello"} 641
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 57348.2 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 608038
telemt_connections_bad_total 5347
telemt_connections_current 871
telemt_connections_me_current 871
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 11707
telemt_upstream_connect_attempt_total 29862
telemt_upstream_connect_success_total 29794
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 29854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 321
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 1325
telemt_me_reconnect_success_total 562
telemt_me_reader_eof_total 546
telemt_me_idle_close_by_peer_total 546
telemt_me_route_drop_no_conn_total 201471
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549505
telemt_me_endpoint_quarantine_total 521
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 484
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_me_writers_active_current 46
telemt_desync_total 2987
telemt_desync_full_logged_total 848
telemt_desync_suppressed_total 2139
telemt_desync_frames_bucket_total{bucket="1_2"} 787
telemt_desync_frames_bucket_total{bucket="3_10"} 1167
telemt_desync_frames_bucket_total{bucket="gt_10"} 1033
telemt_pool_swap_total 60
telemt_pool_force_close_total 1464
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 24319
telemt_me_writer_removed_unexpected_total 529
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1827
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23039
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1388
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22855
telemt_me_writer_teardown_success_total{mode="normal"} 24866
telemt_me_writer_teardown_noop_total 24319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49185
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.668773
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49185
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 492
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 551402
telemt_user_connections_current{user="hello"} 871
telemt_user_octets_from_client{user="hello"} 10540673509 (9.82 GB)
telemt_user_octets_to_client{user="hello"} 259306493403 (241.50 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 139545.4 (38h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10232562
telemt_connections_bad_total 1192416
telemt_connections_current 5632
telemt_connections_me_current 5632
telemt_handshake_timeouts_total 271016
telemt_upstream_connect_attempt_total 53317
telemt_upstream_connect_success_total 53113
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 53270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_reconnect_attempts_total 2052
telemt_me_reconnect_success_total 1099
telemt_me_reader_eof_total 1064
telemt_me_idle_close_by_peer_total 1064
telemt_me_route_drop_no_conn_total 2978463
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 29
telemt_me_route_drop_queue_full_profile_total{profile="high"} 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7643342
telemt_me_endpoint_quarantine_total 976
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1049
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_warm_current 11
telemt_desync_total 31215
telemt_desync_full_logged_total 10261
telemt_desync_suppressed_total 20954
telemt_desync_frames_bucket_total{bucket="1_2"} 7566
telemt_desync_frames_bucket_total{bucket="3_10"} 11441
telemt_desync_frames_bucket_total{bucket="gt_10"} 12208
telemt_pool_swap_total 154
telemt_pool_force_close_total 4183
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 512
telemt_me_draining_writers_reap_progress_total 48068
telemt_me_writer_removed_unexpected_total 1022
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3886
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45237
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4057
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 126
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43885
telemt_me_writer_teardown_success_total{mode="normal"} 49123
telemt_me_writer_teardown_noop_total 48070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97193
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.511974
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97193
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 512
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 959
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7615026
telemt_user_connections_current{user="hello"} 5632
telemt_user_octets_from_client{user="hello"} 147645026940 (137.51 GB)
telemt_user_octets_to_client{user="hello"} 3530718379992 (3.21 TB)
telemt_user_unique_ips_current{user="hello"} 2122
telemt_user_unique_ips_recent_window{user="hello"} 650
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 139542.3 (38h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8952914
telemt_connections_bad_total 1014762
telemt_connections_current 5187
telemt_connections_me_current 5187
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 227949
telemt_upstream_connect_attempt_total 77808
telemt_upstream_connect_success_total 77250
telemt_upstream_connect_fail_total 487
telemt_upstream_connect_attempts_per_request{bucket="1"} 77737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1969
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 487
telemt_me_reconnect_attempts_total 6640
telemt_me_reconnect_success_total 1572
telemt_me_reader_eof_total 1396
telemt_me_idle_close_by_peer_total 1396
telemt_me_seq_mismatch_total 66
telemt_me_route_drop_no_conn_total 3416092
telemt_me_route_drop_channel_closed_total 275
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6854341
telemt_me_endpoint_quarantine_total 1082
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1054
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_warm_current 6
telemt_desync_total 30505
telemt_desync_full_logged_total 10028
telemt_desync_suppressed_total 20477
telemt_desync_frames_bucket_total{bucket="1_2"} 7538
telemt_desync_frames_bucket_total{bucket="3_10"} 11312
telemt_desync_frames_bucket_total{bucket="gt_10"} 11655
telemt_pool_swap_total 151
telemt_pool_force_close_total 4116
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 512
telemt_me_draining_writers_reap_progress_total 46722
telemt_me_writer_removed_unexpected_total 1414
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4547
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43653
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3811
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 305
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42606
telemt_me_writer_teardown_success_total{mode="normal"} 48200
telemt_me_writer_teardown_noop_total 46726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94926
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.849714
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94926
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 512
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1225
telemt_me_writer_restored_fallback_total 90
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 6862198
telemt_user_connections_current{user="hello"} 5187
telemt_user_octets_from_client{user="hello"} 123186566517 (114.73 GB)
telemt_user_octets_to_client{user="hello"} 2830726372495 (2.57 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1977
telemt_user_unique_ips_recent_window{user="hello"} 729
```
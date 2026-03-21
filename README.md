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

# Server Metrics 2026-03-21 23:37:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 9074.0 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145480
telemt_connections_bad_total 11242
telemt_connections_current 758
telemt_connections_me_current 758
telemt_handshake_timeouts_total 7244
telemt_upstream_connect_attempt_total 3654
telemt_upstream_connect_success_total 3653
telemt_upstream_connect_attempts_per_request{bucket="1"} 3653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2299
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 91
telemt_me_reconnect_success_total 57
telemt_me_reader_eof_total 58
telemt_me_idle_close_by_peer_total 58
telemt_me_route_drop_no_conn_total 31244
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118273
telemt_me_endpoint_quarantine_total 58
telemt_me_single_endpoint_shadow_rotate_total 79
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
telemt_me_writers_active_current 48
telemt_me_writers_warm_current 22
telemt_desync_total 691
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 472
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 331
telemt_pool_swap_total 9
telemt_pool_force_close_total 251
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 3219
telemt_me_writer_removed_unexpected_total 54
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 233
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3028
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 247
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2968
telemt_me_writer_teardown_success_total{mode="normal"} 3261
telemt_me_writer_teardown_noop_total 3219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6480
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.706210
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6480
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 52
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 118152
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 1421581128 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 44592310116 (41.53 GB)
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 22440.2 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 657017
telemt_connections_bad_total 32319
telemt_connections_current 692
telemt_connections_me_current 692
telemt_handshake_timeouts_total 25140
telemt_upstream_connect_attempt_total 9413
telemt_upstream_connect_success_total 9251
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 9396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_reconnect_attempts_total 820
telemt_me_reconnect_success_total 279
telemt_me_reader_eof_total 241
telemt_me_idle_close_by_peer_total 241
telemt_me_route_drop_no_conn_total 324001
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 535013
telemt_me_endpoint_quarantine_total 192
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 180
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 2363
telemt_desync_full_logged_total 1351
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 500
telemt_desync_frames_bucket_total{bucket="3_10"} 891
telemt_desync_frames_bucket_total{bucket="gt_10"} 972
telemt_pool_swap_total 24
telemt_pool_force_close_total 680
telemt_me_writer_close_signal_drop_total 54
telemt_me_draining_writers_reap_progress_total 8299
telemt_me_writer_removed_unexpected_total 225
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 716
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7811
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 673
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7619
telemt_me_writer_teardown_success_total{mode="normal"} 8527
telemt_me_writer_teardown_noop_total 8299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16826
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.363470
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16826
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 54
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 193
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 534276
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 8974969540 (8.36 GB)
telemt_user_octets_to_client{user="hello"} 184580190444 (171.90 GB)
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 97300.2 (27h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7405134
telemt_connections_bad_total 582976
telemt_connections_current 2057
telemt_connections_me_current 2057
telemt_handshake_timeouts_total 239590
telemt_upstream_connect_attempt_total 35222
telemt_upstream_connect_success_total 35152
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 35159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1480
telemt_me_reconnect_success_total 734
telemt_me_reader_eof_total 742
telemt_me_idle_close_by_peer_total 742
telemt_me_route_drop_no_conn_total 4492606
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6043833
telemt_me_endpoint_quarantine_total 612
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 721
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
telemt_me_writers_active_current 43
telemt_desync_total 25604
telemt_desync_full_logged_total 8460
telemt_desync_suppressed_total 17144
telemt_desync_frames_bucket_total{bucket="1_2"} 5487
telemt_desync_frames_bucket_total{bucket="3_10"} 10003
telemt_desync_frames_bucket_total{bucket="gt_10"} 10114
telemt_pool_swap_total 105
telemt_pool_force_close_total 3504
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 566
telemt_me_draining_writers_reap_progress_total 32074
telemt_me_writer_removed_unexpected_total 714
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2716
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29649
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28570
telemt_me_writer_teardown_success_total{mode="normal"} 32365
telemt_me_writer_teardown_noop_total 32118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64483
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 152.403815
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64483
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 566
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 654
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6036317
telemt_user_connections_current{user="hello"} 2057
telemt_user_octets_from_client{user="hello"} 103603998424 (96.49 GB)
telemt_user_octets_to_client{user="hello"} 1978121619748 (1.80 TB)
telemt_user_unique_ips_current{user="hello"} 957
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 97301.3 (27h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6086406
telemt_connections_bad_total 577184
telemt_connections_current 1590
telemt_connections_me_current 1590
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 201234
telemt_upstream_connect_attempt_total 39148
telemt_upstream_connect_success_total 38809
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 38988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18772
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1801
telemt_me_reconnect_success_total 765
telemt_me_reader_eof_total 743
telemt_me_idle_close_by_peer_total 743
telemt_me_route_drop_no_conn_total 2161068
telemt_me_route_drop_channel_closed_total 250
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4560131
telemt_me_endpoint_quarantine_total 597
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 740
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 21971
telemt_desync_full_logged_total 7422
telemt_desync_suppressed_total 14549
telemt_desync_frames_bucket_total{bucket="1_2"} 5289
telemt_desync_frames_bucket_total{bucket="3_10"} 8526
telemt_desync_frames_bucket_total{bucket="gt_10"} 8156
telemt_pool_swap_total 107
telemt_pool_force_close_total 3195
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 30611
telemt_me_writer_removed_unexpected_total 717
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2607
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28656
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2996
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27416
telemt_me_writer_teardown_success_total{mode="normal"} 31263
telemt_me_writer_teardown_noop_total 30617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61880
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.843384
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61880
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 661
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4503788
telemt_user_connections_current{user="hello"} 1590
telemt_user_octets_from_client{user="hello"} 137660667433 (128.21 GB)
telemt_user_octets_to_client{user="hello"} 2105287367495 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 803
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 97265.4 (27h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6004112
telemt_connections_bad_total 539009
telemt_connections_current 1602
telemt_connections_me_current 1602
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 191462
telemt_upstream_connect_attempt_total 45578
telemt_upstream_connect_success_total 45271
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 45406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1803
telemt_me_reconnect_success_total 817
telemt_me_reader_eof_total 765
telemt_me_idle_close_by_peer_total 765
telemt_me_route_drop_no_conn_total 2098446
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4484771
telemt_me_endpoint_quarantine_total 654
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 725
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 25
telemt_desync_total 21796
telemt_desync_full_logged_total 7253
telemt_desync_suppressed_total 14543
telemt_desync_frames_bucket_total{bucket="1_2"} 5341
telemt_desync_frames_bucket_total{bucket="3_10"} 8338
telemt_desync_frames_bucket_total{bucket="gt_10"} 8117
telemt_pool_swap_total 104
telemt_pool_force_close_total 3069
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 32065
telemt_me_writer_removed_unexpected_total 731
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2689
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30115
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2854
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28996
telemt_me_writer_teardown_success_total{mode="normal"} 32804
telemt_me_writer_teardown_noop_total 32076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64880
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.310673
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64880
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 707
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4486135
telemt_user_connections_current{user="hello"} 1602
telemt_user_octets_from_client{user="hello"} 131274808271 (122.26 GB)
telemt_user_octets_to_client{user="hello"} 2054200447019 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 747
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 97304.7 (27h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19910589
telemt_connections_bad_total 1453718
telemt_connections_current 2141
telemt_connections_me_current 2141
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 574351
telemt_upstream_connect_attempt_total 188722
telemt_upstream_connect_success_total 171122
telemt_upstream_connect_fail_total 16030
telemt_upstream_connect_attempts_per_request{bucket="1"} 187152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8880
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16030
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64278
telemt_me_reconnect_success_total 2136
telemt_me_reader_eof_total 1332
telemt_me_idle_close_by_peer_total 1331
telemt_me_route_drop_no_conn_total 39440575
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16224755
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 743
telemt_me_single_endpoint_outage_enter_total 122
telemt_me_single_endpoint_outage_exit_total 122
telemt_me_single_endpoint_outage_reconnect_attempt_total 258
telemt_me_single_endpoint_outage_reconnect_success_total 61
telemt_me_single_endpoint_quarantine_bypass_total 258
telemt_me_single_endpoint_shadow_rotate_total 759
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
telemt_me_writers_warm_current 35
telemt_desync_total 31235
telemt_desync_full_logged_total 9280
telemt_desync_suppressed_total 21955
telemt_desync_frames_bucket_total{bucket="1_2"} 6816
telemt_desync_frames_bucket_total{bucket="3_10"} 13830
telemt_desync_frames_bucket_total{bucket="gt_10"} 10589
telemt_pool_swap_total 99
telemt_pool_force_close_total 3287
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 749
telemt_me_draining_writers_reap_progress_total 30129
telemt_me_writer_removed_unexpected_total 1993
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4157
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27699
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2771
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26842
telemt_me_writer_teardown_success_total{mode="normal"} 31856
telemt_me_writer_teardown_noop_total 30155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62011
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 210.124606
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62011
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 749
telemt_me_refill_failed_total 3787
telemt_me_writer_restored_same_endpoint_total 1478
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14672
telemt_me_writer_removed_unexpected_minus_restored_total 494
telemt_user_connections_total{user="hello"} 16352737
telemt_user_connections_current{user="hello"} 2141
telemt_user_octets_from_client{user="hello"} 182944353180 (170.38 GB)
telemt_user_octets_to_client{user="hello"} 1102066975150 (1.00 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 1026
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 97272.3 (27h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5801345
telemt_connections_bad_total 542280
telemt_connections_current 1565
telemt_connections_me_current 1565
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 119623
telemt_upstream_connect_attempt_total 53644
telemt_upstream_connect_success_total 53030
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 53553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21074
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_reconnect_attempts_total 68084
telemt_me_reconnect_success_total 1678
telemt_me_reader_eof_total 1457
telemt_me_idle_close_by_peer_total 1456
telemt_me_route_drop_no_conn_total 2351863
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4524544
telemt_me_endpoint_quarantine_total 637
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 726
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_warm_current 27
telemt_desync_total 22873
telemt_desync_full_logged_total 7992
telemt_desync_suppressed_total 14881
telemt_desync_frames_bucket_total{bucket="1_2"} 4338
telemt_desync_frames_bucket_total{bucket="3_10"} 8854
telemt_desync_frames_bucket_total{bucket="gt_10"} 9681
telemt_pool_swap_total 99
telemt_pool_force_close_total 2921
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 33367
telemt_me_writer_removed_unexpected_total 1503
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3566
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31327
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2520
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30446
telemt_me_writer_teardown_success_total{mode="normal"} 34893
telemt_me_writer_teardown_noop_total 33368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68261
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.873867
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68261
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 1422
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4517670
telemt_user_connections_current{user="hello"} 1565
telemt_user_octets_from_client{user="hello"} 121588082764 (113.24 GB)
telemt_user_octets_to_client{user="hello"} 1844935872130 (1.68 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 754
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 34108.0 (9h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3672724
telemt_connections_bad_total 129975
telemt_connections_current 1229
telemt_connections_me_current 1229
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1533884
telemt_upstream_connect_attempt_total 21838
telemt_upstream_connect_success_total 21702
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 21831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_reconnect_attempts_total 45581
telemt_me_reconnect_success_total 880
telemt_me_reader_eof_total 552
telemt_me_idle_close_by_peer_total 552
telemt_me_route_drop_no_conn_total 990559
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1770856
telemt_me_endpoint_quarantine_total 233
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 254
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9843
telemt_desync_full_logged_total 3364
telemt_desync_suppressed_total 6479
telemt_desync_frames_bucket_total{bucket="1_2"} 1740
telemt_desync_frames_bucket_total{bucket="3_10"} 3765
telemt_desync_frames_bucket_total{bucket="gt_10"} 4338
telemt_pool_swap_total 36
telemt_pool_force_close_total 1202
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 11372
telemt_me_writer_removed_unexpected_total 633
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1268
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10756
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 996
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10170
telemt_me_writer_teardown_success_total{mode="normal"} 12024
telemt_me_writer_teardown_noop_total 11374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23398
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.997601
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23398
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 2597
telemt_me_writer_restored_same_endpoint_total 791
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1774607
telemt_user_connections_current{user="hello"} 1229
telemt_user_octets_from_client{user="hello"} 51916481296 (48.35 GB)
telemt_user_octets_to_client{user="hello"} 761888700990 (709.56 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 659
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 15079.2 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154049
telemt_connections_bad_total 1392
telemt_connections_current 299
telemt_connections_me_current 299
telemt_handshake_timeouts_total 3695
telemt_upstream_connect_attempt_total 6824
telemt_upstream_connect_success_total 6807
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 138
telemt_me_reconnect_success_total 92
telemt_me_reader_eof_total 93
telemt_me_idle_close_by_peer_total 93
telemt_me_route_drop_no_conn_total 43828
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134889
telemt_me_endpoint_quarantine_total 130
telemt_me_single_endpoint_shadow_rotate_total 133
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 958
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 718
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 16
telemt_pool_force_close_total 381
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 6088
telemt_me_writer_removed_unexpected_total 91
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 405
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5776
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 379
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5707
telemt_me_writer_teardown_success_total{mode="normal"} 6181
telemt_me_writer_teardown_noop_total 6088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12269
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.736529
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12269
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 134677
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 2513639148 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 79173818636 (73.74 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 97276.6 (27h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6969424
telemt_connections_bad_total 708547
telemt_connections_current 1834
telemt_connections_me_current 1834
telemt_handshake_timeouts_total 198303
telemt_upstream_connect_attempt_total 37118
telemt_upstream_connect_success_total 36973
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 37081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18565
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_reconnect_attempts_total 1489
telemt_me_reconnect_success_total 777
telemt_me_reader_eof_total 755
telemt_me_idle_close_by_peer_total 755
telemt_me_route_drop_no_conn_total 2091061
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5282156
telemt_me_endpoint_quarantine_total 654
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 742
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 29
telemt_desync_total 20378
telemt_desync_full_logged_total 6791
telemt_desync_suppressed_total 13587
telemt_desync_frames_bucket_total{bucket="1_2"} 4981
telemt_desync_frames_bucket_total{bucket="3_10"} 7394
telemt_desync_frames_bucket_total{bucket="gt_10"} 8003
telemt_pool_swap_total 107
telemt_pool_force_close_total 2924
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 363
telemt_me_draining_writers_reap_progress_total 33355
telemt_me_writer_removed_unexpected_total 731
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2695
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31405
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2836
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30431
telemt_me_writer_teardown_success_total{mode="normal"} 34100
telemt_me_writer_teardown_noop_total 33357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67457
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.512712
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67457
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 363
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 693
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 5257413
telemt_user_connections_current{user="hello"} 1834
telemt_user_octets_from_client{user="hello"} 105486484464 (98.24 GB)
telemt_user_octets_to_client{user="hello"} 2469416246608 (2.25 TB)
telemt_user_unique_ips_current{user="hello"} 784
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 97273.3 (27h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5976549
telemt_connections_bad_total 584208
telemt_connections_current 1765
telemt_connections_me_current 1765
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 166551
telemt_upstream_connect_attempt_total 53146
telemt_upstream_connect_success_total 52743
telemt_upstream_connect_fail_total 344
telemt_upstream_connect_attempts_per_request{bucket="1"} 53087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20349
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 344
telemt_me_reconnect_attempts_total 5290
telemt_me_reconnect_success_total 1080
telemt_me_reader_eof_total 956
telemt_me_idle_close_by_peer_total 956
telemt_me_seq_mismatch_total 41
telemt_me_route_drop_no_conn_total 2144847
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4652967
telemt_me_endpoint_quarantine_total 759
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 738
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 22
telemt_desync_total 19154
telemt_desync_full_logged_total 6431
telemt_desync_suppressed_total 12723
telemt_desync_frames_bucket_total{bucket="1_2"} 4804
telemt_desync_frames_bucket_total{bucket="3_10"} 6970
telemt_desync_frames_bucket_total{bucket="gt_10"} 7380
telemt_pool_swap_total 105
telemt_pool_force_close_total 2883
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 364
telemt_me_draining_writers_reap_progress_total 32175
telemt_me_writer_removed_unexpected_total 969
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3180
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30007
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2660
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29292
telemt_me_writer_teardown_success_total{mode="normal"} 33187
telemt_me_writer_teardown_noop_total 32179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65366
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.727477
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65366
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 364
telemt_me_refill_failed_total 243
telemt_me_writer_restored_same_endpoint_total 838
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 4656310
telemt_user_connections_current{user="hello"} 1765
telemt_user_octets_from_client{user="hello"} 88462503297 (82.39 GB)
telemt_user_octets_to_client{user="hello"} 2000710369536 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 799
telemt_user_unique_ips_recent_window{user="hello"} 170
```
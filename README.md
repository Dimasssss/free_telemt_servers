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

# Server Metrics 2026-03-22 02:41:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 20079.5 (5h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291172
telemt_connections_bad_total 19881
telemt_connections_current 756
telemt_connections_me_current 756
telemt_handshake_timeouts_total 16784
telemt_upstream_connect_attempt_total 8426
telemt_upstream_connect_success_total 8425
telemt_upstream_connect_attempts_per_request{bucket="1"} 8425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 258
telemt_me_reconnect_success_total 135
telemt_me_reader_eof_total 130
telemt_me_idle_close_by_peer_total 130
telemt_me_route_drop_no_conn_total 56041
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239142
telemt_me_endpoint_quarantine_total 169
telemt_me_single_endpoint_shadow_rotate_total 172
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 49
telemt_desync_total 2123
telemt_desync_full_logged_total 579
telemt_desync_suppressed_total 1544
telemt_desync_frames_bucket_total{bucket="1_2"} 701
telemt_desync_frames_bucket_total{bucket="3_10"} 784
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 22
telemt_pool_force_close_total 575
telemt_me_writer_close_signal_drop_total 39
telemt_me_draining_writers_reap_progress_total 7585
telemt_me_writer_removed_unexpected_total 130
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 526
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7179
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 570
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7010
telemt_me_writer_teardown_success_total{mode="normal"} 7705
telemt_me_writer_teardown_noop_total 7586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15291
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.899570
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15291
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 39
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 238672
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 2716108116 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 88254400860 (82.19 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 33446.2 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 790194
telemt_connections_bad_total 48194
telemt_connections_current 800
telemt_connections_me_current 800
telemt_handshake_timeouts_total 29160
telemt_upstream_connect_attempt_total 15519
telemt_upstream_connect_success_total 15270
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 15496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_reconnect_attempts_total 1351
telemt_me_reconnect_success_total 487
telemt_me_reader_eof_total 431
telemt_me_idle_close_by_peer_total 431
telemt_me_route_drop_no_conn_total 341138
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 625294
telemt_me_endpoint_quarantine_total 320
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 269
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 40
telemt_desync_total 2716
telemt_desync_full_logged_total 1561
telemt_desync_suppressed_total 1155
telemt_desync_frames_bucket_total{bucket="1_2"} 580
telemt_desync_frames_bucket_total{bucket="3_10"} 1034
telemt_desync_frames_bucket_total{bucket="gt_10"} 1102
telemt_pool_swap_total 36
telemt_pool_force_close_total 959
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 13730
telemt_me_writer_removed_unexpected_total 408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1157
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12991
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 937
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12771
telemt_me_writer_teardown_success_total{mode="normal"} 14148
telemt_me_writer_teardown_noop_total 13730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27878
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.706967
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27878
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 358
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 624389
telemt_user_connections_current{user="hello"} 800
telemt_user_octets_from_client{user="hello"} 10222394284 (9.52 GB)
telemt_user_octets_to_client{user="hello"} 222305264668 (207.04 GB)
telemt_user_unique_ips_current{user="hello"} 541
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 108306.1 (30h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7742252
telemt_connections_bad_total 629721
telemt_connections_current 1359
telemt_connections_me_current 1359
telemt_handshake_timeouts_total 254577
telemt_upstream_connect_attempt_total 40172
telemt_upstream_connect_success_total 40098
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 40105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21765
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1572
telemt_me_reconnect_success_total 812
telemt_me_reader_eof_total 821
telemt_me_idle_close_by_peer_total 821
telemt_me_route_drop_no_conn_total 4535941
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6266329
telemt_me_endpoint_quarantine_total 697
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 809
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 26443
telemt_desync_full_logged_total 8748
telemt_desync_suppressed_total 17695
telemt_desync_frames_bucket_total{bucket="1_2"} 5701
telemt_desync_frames_bucket_total{bucket="3_10"} 10328
telemt_desync_frames_bucket_total{bucket="gt_10"} 10414
telemt_pool_swap_total 117
telemt_pool_force_close_total 3891
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 603
telemt_me_draining_writers_reap_progress_total 36673
telemt_me_writer_removed_unexpected_total 790
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3060
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33937
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3652
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32782
telemt_me_writer_teardown_success_total{mode="normal"} 36997
telemt_me_writer_teardown_noop_total 36717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73714
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 159.872908
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73714
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 603
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 722
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6258454
telemt_user_connections_current{user="hello"} 1359
telemt_user_octets_from_client{user="hello"} 106326414576 (99.02 GB)
telemt_user_octets_to_client{user="hello"} 2081869847904 (1.89 TB)
telemt_user_unique_ips_current{user="hello"} 659
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 108307.9 (30h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6389933
telemt_connections_bad_total 587008
telemt_connections_current 1583
telemt_connections_me_current 1583
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 211337
telemt_upstream_connect_attempt_total 44190
telemt_upstream_connect_success_total 43802
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 43993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21460
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1940
telemt_me_reconnect_success_total 870
telemt_me_reader_eof_total 842
telemt_me_idle_close_by_peer_total 842
telemt_me_route_drop_no_conn_total 2256973
telemt_me_route_drop_channel_closed_total 261
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4776892
telemt_me_endpoint_quarantine_total 679
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 833
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
telemt_me_writers_active_current 46
telemt_desync_total 22570
telemt_desync_full_logged_total 7685
telemt_desync_suppressed_total 14885
telemt_desync_frames_bucket_total{bucket="1_2"} 5432
telemt_desync_frames_bucket_total{bucket="3_10"} 8760
telemt_desync_frames_bucket_total{bucket="gt_10"} 8378
telemt_pool_swap_total 118
telemt_pool_force_close_total 3518
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 35189
telemt_me_writer_removed_unexpected_total 827
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2942
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33011
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3305
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31671
telemt_me_writer_teardown_success_total{mode="normal"} 35953
telemt_me_writer_teardown_noop_total 35195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71148
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.303862
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71148
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 761
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 4699043
telemt_user_connections_current{user="hello"} 1583
telemt_user_octets_from_client{user="hello"} 140274684317 (130.64 GB)
telemt_user_octets_to_client{user="hello"} 2218921591883 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 724
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 108272.9 (30h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6271557
telemt_connections_bad_total 547710
telemt_connections_current 1387
telemt_connections_me_current 1387
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 203107
telemt_upstream_connect_attempt_total 50325
telemt_upstream_connect_success_total 49958
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 50094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22848
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1070
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2045
telemt_me_reconnect_success_total 904
telemt_me_reader_eof_total 849
telemt_me_idle_close_by_peer_total 849
telemt_me_route_drop_no_conn_total 2150501
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4667691
telemt_me_endpoint_quarantine_total 758
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 809
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 22444
telemt_desync_full_logged_total 7552
telemt_desync_suppressed_total 14892
telemt_desync_frames_bucket_total{bucket="1_2"} 5481
telemt_desync_frames_bucket_total{bucket="3_10"} 8594
telemt_desync_frames_bucket_total{bucket="gt_10"} 8369
telemt_pool_swap_total 117
telemt_pool_force_close_total 3403
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 386
telemt_me_draining_writers_reap_progress_total 36346
telemt_me_writer_removed_unexpected_total 821
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3016
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34165
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32943
telemt_me_writer_teardown_success_total{mode="normal"} 37181
telemt_me_writer_teardown_noop_total 36358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73539
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.046680
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73539
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 386
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 784
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 4663294
telemt_user_connections_current{user="hello"} 1387
telemt_user_octets_from_client{user="hello"} 133672255579 (124.49 GB)
telemt_user_octets_to_client{user="hello"} 2133012262715 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 648
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 108310.3 (30h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20408796
telemt_connections_bad_total 1619825
telemt_connections_current 2170
telemt_connections_me_current 2170
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 606107
telemt_upstream_connect_attempt_total 199275
telemt_upstream_connect_success_total 181183
telemt_upstream_connect_fail_total 16338
telemt_upstream_connect_attempts_per_request{bucket="1"} 197521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42757
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8929
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16338
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64900
telemt_me_reconnect_success_total 2328
telemt_me_reader_eof_total 1457
telemt_me_idle_close_by_peer_total 1456
telemt_me_route_drop_no_conn_total 39507917
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16496685
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 855
telemt_me_single_endpoint_outage_enter_total 135
telemt_me_single_endpoint_outage_exit_total 135
telemt_me_single_endpoint_outage_reconnect_attempt_total 285
telemt_me_single_endpoint_outage_reconnect_success_total 70
telemt_me_single_endpoint_quarantine_bypass_total 285
telemt_me_single_endpoint_shadow_rotate_total 848
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 64
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
telemt_desync_total 31933
telemt_desync_full_logged_total 9577
telemt_desync_suppressed_total 22356
telemt_desync_frames_bucket_total{bucket="1_2"} 6914
telemt_desync_frames_bucket_total{bucket="3_10"} 14174
telemt_desync_frames_bucket_total{bucket="gt_10"} 10845
telemt_pool_swap_total 112
telemt_pool_force_close_total 3626
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 794
telemt_me_draining_writers_reap_progress_total 33999
telemt_me_writer_removed_unexpected_total 2156
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4603
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31292
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30373
telemt_me_writer_teardown_success_total{mode="normal"} 35895
telemt_me_writer_teardown_noop_total 34025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69920
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.679293
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69920
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 794
telemt_me_refill_failed_total 3802
telemt_me_writer_restored_same_endpoint_total 1596
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 539
telemt_user_connections_total{user="hello"} 16629848
telemt_user_connections_current{user="hello"} 2170
telemt_user_octets_from_client{user="hello"} 218476801184 (203.47 GB)
telemt_user_octets_to_client{user="hello"} 1199158338041 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 395497
telemt_user_msgs_to_client{user="hello"} 785476
telemt_user_unique_ips_current{user="hello"} 988
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 108277.6 (30h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6025237
telemt_connections_bad_total 567504
telemt_connections_current 1041
telemt_connections_me_current 1041
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 126521
telemt_upstream_connect_attempt_total 58939
telemt_upstream_connect_success_total 58259
telemt_upstream_connect_fail_total 582
telemt_upstream_connect_attempts_per_request{bucket="1"} 58841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 582
telemt_me_reconnect_attempts_total 69650
telemt_me_reconnect_success_total 1787
telemt_me_reader_eof_total 1566
telemt_me_idle_close_by_peer_total 1565
telemt_me_route_drop_no_conn_total 2388865
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4697994
telemt_me_endpoint_quarantine_total 736
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 820
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 23351
telemt_desync_full_logged_total 8231
telemt_desync_suppressed_total 15120
telemt_desync_frames_bucket_total{bucket="1_2"} 4446
telemt_desync_frames_bucket_total{bucket="3_10"} 9047
telemt_desync_frames_bucket_total{bucket="gt_10"} 9858
telemt_pool_swap_total 112
telemt_pool_force_close_total 3223
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 395
telemt_me_draining_writers_reap_progress_total 38152
telemt_me_writer_removed_unexpected_total 1604
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3923
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35864
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2822
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34929
telemt_me_writer_teardown_success_total{mode="normal"} 39787
telemt_me_writer_teardown_noop_total 38153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77940
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.124720
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77940
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 395
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1498
telemt_me_writer_restored_fallback_total 34
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 4690807
telemt_user_connections_current{user="hello"} 1041
telemt_user_octets_from_client{user="hello"} 124396032620 (115.85 GB)
telemt_user_octets_to_client{user="hello"} 1913206271898 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 45113.5 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3921527
telemt_connections_bad_total 144293
telemt_connections_current 1647
telemt_connections_me_current 1647
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1597862
telemt_upstream_connect_attempt_total 27489
telemt_upstream_connect_success_total 27312
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 27482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10004
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_reconnect_attempts_total 45818
telemt_me_reconnect_success_total 966
telemt_me_reader_eof_total 648
telemt_me_idle_close_by_peer_total 648
telemt_me_route_drop_no_conn_total 1021964
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1923199
telemt_me_endpoint_quarantine_total 338
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 345
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10454
telemt_desync_full_logged_total 3606
telemt_desync_suppressed_total 6848
telemt_desync_frames_bucket_total{bucket="1_2"} 1876
telemt_desync_frames_bucket_total{bucket="3_10"} 4008
telemt_desync_frames_bucket_total{bucket="gt_10"} 4570
telemt_pool_swap_total 49
telemt_pool_force_close_total 1470
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 134
telemt_me_draining_writers_reap_progress_total 16512
telemt_me_writer_removed_unexpected_total 722
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1518
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15742
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15042
telemt_me_writer_teardown_success_total{mode="normal"} 17260
telemt_me_writer_teardown_noop_total 16514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33774
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.440449
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33774
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 134
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 865
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1926819
telemt_user_connections_current{user="hello"} 1647
telemt_user_octets_from_client{user="hello"} 54025368684 (50.32 GB)
telemt_user_octets_to_client{user="hello"} 819259604018 (762.99 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 831
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 26084.5 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196248
telemt_connections_bad_total 1653
telemt_connections_current 306
telemt_connections_me_current 306
telemt_handshake_timeouts_total 5392
telemt_upstream_connect_attempt_total 12526
telemt_upstream_connect_success_total 12496
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 12524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 248
telemt_me_reconnect_success_total 162
telemt_me_reader_eof_total 166
telemt_me_idle_close_by_peer_total 166
telemt_me_route_drop_no_conn_total 53827
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172924
telemt_me_endpoint_quarantine_total 250
telemt_me_single_endpoint_shadow_rotate_total 226
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 1026
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 767
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 381
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 28
telemt_pool_force_close_total 625
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 11298
telemt_me_writer_removed_unexpected_total 159
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10734
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 623
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10673
telemt_me_writer_teardown_success_total{mode="normal"} 11464
telemt_me_writer_teardown_noop_total 11298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22762
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.976987
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22762
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 148
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 172610
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 3093212608 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 106045999836 (98.76 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 108282.0 (30h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7332386
telemt_connections_bad_total 741974
telemt_connections_current 1618
telemt_connections_me_current 1618
telemt_handshake_timeouts_total 209206
telemt_upstream_connect_attempt_total 42455
telemt_upstream_connect_success_total 42298
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 42418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_reconnect_attempts_total 1586
telemt_me_reconnect_success_total 852
telemt_me_reader_eof_total 835
telemt_me_idle_close_by_peer_total 835
telemt_me_route_drop_no_conn_total 2127037
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5481638
telemt_me_endpoint_quarantine_total 763
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 835
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 21488
telemt_desync_full_logged_total 7050
telemt_desync_suppressed_total 14438
telemt_desync_frames_bucket_total{bucket="1_2"} 5407
telemt_desync_frames_bucket_total{bucket="3_10"} 7763
telemt_desync_frames_bucket_total{bucket="gt_10"} 8318
telemt_pool_swap_total 120
telemt_pool_force_close_total 3213
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 388
telemt_me_draining_writers_reap_progress_total 38278
telemt_me_writer_removed_unexpected_total 806
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3016
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36087
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3125
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35065
telemt_me_writer_teardown_success_total{mode="normal"} 39103
telemt_me_writer_teardown_noop_total 38280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77383
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.644871
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77383
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 388
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 762
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 5456666
telemt_user_connections_current{user="hello"} 1618
telemt_user_octets_from_client{user="hello"} 109538293272 (102.02 GB)
telemt_user_octets_to_client{user="hello"} 2541365916248 (2.31 TB)
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 108278.7 (30h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6327458
telemt_connections_bad_total 625009
telemt_connections_current 1515
telemt_connections_me_current 1515
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 172585
telemt_upstream_connect_attempt_total 58252
telemt_upstream_connect_success_total 57814
telemt_upstream_connect_fail_total 379
telemt_upstream_connect_attempts_per_request{bucket="1"} 58193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23014
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 379
telemt_me_reconnect_attempts_total 5573
telemt_me_reconnect_success_total 1175
telemt_me_reader_eof_total 1061
telemt_me_idle_close_by_peer_total 1061
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 2179929
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4848098
telemt_me_endpoint_quarantine_total 859
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 830
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 20118
telemt_desync_full_logged_total 6695
telemt_desync_suppressed_total 13423
telemt_desync_frames_bucket_total{bucket="1_2"} 5143
telemt_desync_frames_bucket_total{bucket="3_10"} 7334
telemt_desync_frames_bucket_total{bucket="gt_10"} 7641
telemt_pool_swap_total 118
telemt_pool_force_close_total 3174
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 381
telemt_me_draining_writers_reap_progress_total 36845
telemt_me_writer_removed_unexpected_total 1071
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3545
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34424
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2951
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33671
telemt_me_writer_teardown_success_total{mode="normal"} 37969
telemt_me_writer_teardown_noop_total 36849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74818
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.084466
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74818
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 381
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 918
telemt_me_writer_restored_fallback_total 63
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4851118
telemt_user_connections_current{user="hello"} 1515
telemt_user_octets_from_client{user="hello"} 91503242621 (85.22 GB)
telemt_user_octets_to_client{user="hello"} 2071919798604 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 663
telemt_user_unique_ips_recent_window{user="hello"} 162
```
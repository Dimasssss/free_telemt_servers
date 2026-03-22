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

# Server Metrics 2026-03-22 18:27:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 76861.6 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2804514
telemt_connections_bad_total 172004
telemt_connections_current 1413
telemt_connections_me_current 1413
telemt_handshake_timeouts_total 95506
telemt_upstream_connect_attempt_total 28200
telemt_upstream_connect_success_total 28199
telemt_upstream_connect_attempts_per_request{bucket="1"} 28199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18322
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 68
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1146
telemt_me_reconnect_success_total 480
telemt_me_reader_eof_total 483
telemt_me_idle_close_by_peer_total 483
telemt_me_route_drop_no_conn_total 2315839
telemt_me_route_drop_channel_closed_total 959
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2379110
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 519
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 601
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_me_writers_active_current 42
telemt_desync_total 10758
telemt_desync_full_logged_total 3410
telemt_desync_suppressed_total 7348
telemt_desync_frames_bucket_total{bucket="1_2"} 2890
telemt_desync_frames_bucket_total{bucket="3_10"} 3988
telemt_desync_frames_bucket_total{bucket="gt_10"} 3880
telemt_pool_swap_total 85
telemt_pool_force_close_total 2639
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 547
telemt_me_draining_writers_reap_progress_total 25764
telemt_me_writer_removed_unexpected_total 469
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1887
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24104
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2586
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23125
telemt_me_writer_teardown_success_total{mode="normal"} 25991
telemt_me_writer_teardown_noop_total 25774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51765
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 261.808031
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51765
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 547
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 425
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2375212
telemt_user_connections_current{user="hello"} 1413
telemt_user_octets_from_client{user="hello"} 34837830696 (32.45 GB)
telemt_user_octets_to_client{user="hello"} 629544086552 (586.31 GB)
telemt_user_unique_ips_current{user="hello"} 542
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 90228.1 (25h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3741537
telemt_connections_bad_total 336745
telemt_connections_current 666
telemt_connections_me_current 666
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 95124
telemt_upstream_connect_attempt_total 55413
telemt_upstream_connect_success_total 54731
telemt_upstream_connect_fail_total 601
telemt_upstream_connect_attempts_per_request{bucket="1"} 55332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 601
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6356
telemt_me_reconnect_success_total 2331
telemt_me_reader_eof_total 2263
telemt_me_idle_close_by_peer_total 2263
telemt_me_route_drop_no_conn_total 3576966
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2971718
telemt_me_endpoint_quarantine_total 711
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 695
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_me_writers_active_current 41
telemt_desync_total 11775
telemt_desync_full_logged_total 6581
telemt_desync_suppressed_total 5194
telemt_desync_frames_bucket_total{bucket="1_2"} 2715
telemt_desync_frames_bucket_total{bucket="3_10"} 4607
telemt_desync_frames_bucket_total{bucket="gt_10"} 4453
telemt_pool_swap_total 85
telemt_pool_force_close_total 2572
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 35941
telemt_me_writer_removed_unexpected_total 2214
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4276
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33890
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33369
telemt_me_writer_teardown_success_total{mode="normal"} 38166
telemt_me_writer_teardown_noop_total 35941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74107
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.329751
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74107
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 2019
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 2982574
telemt_user_connections_current{user="hello"} 666
telemt_user_octets_from_client{user="hello"} 38546340663 (35.90 GB)
telemt_user_octets_to_client{user="hello"} 690060544702 (642.67 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 165088.0 (45h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15706095
telemt_connections_bad_total 1503035
telemt_connections_current 2142
telemt_connections_me_current 2142
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 388160
telemt_upstream_connect_attempt_total 73844
telemt_upstream_connect_success_total 73747
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 73764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2752
telemt_me_reconnect_success_total 1407
telemt_me_reader_eof_total 1346
telemt_me_idle_close_by_peer_total 1344
telemt_me_route_drop_no_conn_total 13907129
telemt_me_route_drop_channel_closed_total 142
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12520887
telemt_me_endpoint_quarantine_total 1042
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1231
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
telemt_me_writers_active_current 44
telemt_desync_total 51480
telemt_desync_full_logged_total 16175
telemt_desync_suppressed_total 35305
telemt_desync_frames_bucket_total{bucket="1_2"} 11494
telemt_desync_frames_bucket_total{bucket="3_10"} 20057
telemt_desync_frames_bucket_total{bucket="gt_10"} 19929
telemt_pool_swap_total 178
telemt_pool_force_close_total 6026
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 972
telemt_me_draining_writers_reap_progress_total 54213
telemt_me_writer_removed_unexpected_total 1300
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4749
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50055
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5561
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 465
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48187
telemt_me_writer_teardown_success_total{mode="normal"} 54804
telemt_me_writer_teardown_noop_total 54263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109067
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 305.754067
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109067
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 972
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1211
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12521658
telemt_user_connections_current{user="hello"} 2142
telemt_user_octets_from_client{user="hello"} 181903585129 (169.41 GB)
telemt_user_octets_to_client{user="hello"} 3279783542803 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 855
telemt_user_unique_ips_recent_window{user="hello"} 330
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 165089.3 (45h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11338306
telemt_connections_bad_total 1120191
telemt_connections_current 1687
telemt_connections_me_current 1687
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 339262
telemt_upstream_connect_attempt_total 86333
telemt_upstream_connect_success_total 85131
telemt_upstream_connect_fail_total 840
telemt_upstream_connect_attempts_per_request{bucket="1"} 85971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35101
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3702
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 840
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4094
telemt_me_reconnect_success_total 1689
telemt_me_reader_eof_total 1558
telemt_me_idle_close_by_peer_total 1558
telemt_me_route_drop_no_conn_total 4438890
telemt_me_route_drop_channel_closed_total 490
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8444494
telemt_me_endpoint_quarantine_total 1046
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1249
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 37568
telemt_desync_full_logged_total 12638
telemt_desync_suppressed_total 24930
telemt_desync_frames_bucket_total{bucket="1_2"} 9249
telemt_desync_frames_bucket_total{bucket="3_10"} 14475
telemt_desync_frames_bucket_total{bucket="gt_10"} 13844
telemt_pool_swap_total 175
telemt_pool_force_close_total 5443
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 690
telemt_me_draining_writers_reap_progress_total 52677
telemt_me_writer_removed_unexpected_total 1597
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4874
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49244
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4945
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 498
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47234
telemt_me_writer_teardown_success_total{mode="normal"} 54118
telemt_me_writer_teardown_noop_total 52700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106818
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 102.802178
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106818
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 690
telemt_me_refill_failed_total 130
telemt_me_writer_restored_same_endpoint_total 1446
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 8382909
telemt_user_connections_current{user="hello"} 1687
telemt_user_octets_from_client{user="hello"} 209851720185 (195.44 GB)
telemt_user_octets_to_client{user="hello"} 3780407643274 (3.44 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 635
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 165054.8 (45h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10671894
telemt_connections_bad_total 919461
telemt_connections_current 1237
telemt_connections_me_current 1237
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 341895
telemt_upstream_connect_attempt_total 71437
telemt_upstream_connect_success_total 70415
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 70598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33584
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4885
telemt_me_reconnect_success_total 1961
telemt_me_reader_eof_total 1714
telemt_me_idle_close_by_peer_total 1713
telemt_me_route_drop_no_conn_total 5206106
telemt_me_route_drop_channel_closed_total 371
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8059442
telemt_me_endpoint_quarantine_total 1122
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1213
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 37112
telemt_desync_full_logged_total 12272
telemt_desync_suppressed_total 24840
telemt_desync_frames_bucket_total{bucket="1_2"} 9395
telemt_desync_frames_bucket_total{bucket="3_10"} 14206
telemt_desync_frames_bucket_total{bucket="gt_10"} 13511
telemt_pool_swap_total 173
telemt_pool_force_close_total 5376
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 699
telemt_me_draining_writers_reap_progress_total 52895
telemt_me_writer_removed_unexpected_total 1855
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5313
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49354
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4831
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47519
telemt_me_writer_teardown_success_total{mode="normal"} 54667
telemt_me_writer_teardown_noop_total 52966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107633
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.506530
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107633
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 699
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 1694
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8052042
telemt_user_connections_current{user="hello"} 1237
telemt_user_octets_from_client{user="hello"} 185982225729 (173.21 GB)
telemt_user_octets_to_client{user="hello"} 3353442687105 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 35333.4 (9h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10551513
telemt_connections_bad_total 645468
telemt_connections_current 2255
telemt_connections_me_current 2255
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 215611
telemt_upstream_connect_attempt_total 42415
telemt_upstream_connect_success_total 40287
telemt_upstream_connect_fail_total 1489
telemt_upstream_connect_attempts_per_request{bucket="1"} 41776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5924
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1489
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6323
telemt_me_reconnect_success_total 813
telemt_me_reader_eof_total 516
telemt_me_idle_close_by_peer_total 516
telemt_me_route_drop_no_conn_total 25103561
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8766689
telemt_me_endpoint_quarantine_total 222
telemt_me_single_endpoint_outage_enter_total 61
telemt_me_single_endpoint_outage_exit_total 61
telemt_me_single_endpoint_outage_reconnect_attempt_total 112
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 112
telemt_me_single_endpoint_shadow_rotate_total 279
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
telemt_me_writers_active_current 43
telemt_desync_total 14009
telemt_desync_full_logged_total 3652
telemt_desync_suppressed_total 10357
telemt_desync_frames_bucket_total{bucket="1_2"} 2581
telemt_desync_frames_bucket_total{bucket="3_10"} 5681
telemt_desync_frames_bucket_total{bucket="gt_10"} 5747
telemt_pool_swap_total 35
telemt_pool_force_close_total 1316
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 9989
telemt_me_writer_removed_unexpected_total 718
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1524
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9141
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1030
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 286
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8673
telemt_me_writer_teardown_success_total{mode="normal"} 10665
telemt_me_writer_teardown_noop_total 9995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20660
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 44.882118
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20660
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 305
telemt_me_writer_restored_same_endpoint_total 542
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 8788263
telemt_user_connections_current{user="hello"} 2255
telemt_user_octets_from_client{user="hello"} 77244766483 (71.94 GB)
telemt_user_octets_to_client{user="hello"} 411111722953 (382.88 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 781
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 165060.1 (45h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10515620
telemt_connections_bad_total 886773
telemt_connections_current 1982
telemt_connections_me_current 1982
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 232492
telemt_upstream_connect_attempt_total 100294
telemt_upstream_connect_success_total 99241
telemt_upstream_connect_fail_total 897
telemt_upstream_connect_attempts_per_request{bucket="1"} 100138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1322
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 897
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72190
telemt_me_reconnect_success_total 2717
telemt_me_reader_eof_total 2409
telemt_me_idle_close_by_peer_total 2407
telemt_me_route_drop_no_conn_total 5139905
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8298479
telemt_me_endpoint_quarantine_total 1098
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1233
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 43934
telemt_desync_full_logged_total 14994
telemt_desync_suppressed_total 28940
telemt_desync_frames_bucket_total{bucket="1_2"} 8918
telemt_desync_frames_bucket_total{bucket="3_10"} 16874
telemt_desync_frames_bucket_total{bucket="gt_10"} 18142
telemt_pool_swap_total 169
telemt_pool_force_close_total 5032
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 623
telemt_me_draining_writers_reap_progress_total 56151
telemt_me_writer_removed_unexpected_total 2449
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5992
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52632
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4336
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 696
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51119
telemt_me_writer_teardown_success_total{mode="normal"} 58624
telemt_me_writer_teardown_noop_total 56152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114776
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.847787
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114776
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 623
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2275
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8302019
telemt_user_connections_current{user="hello"} 1982
telemt_user_octets_from_client{user="hello"} 188358486425 (175.42 GB)
telemt_user_octets_to_client{user="hello"} 3147569209740 (2.86 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 664
telemt_user_unique_ips_recent_window{user="hello"} 319
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 101896.1 (28h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11026032
telemt_connections_bad_total 425810
telemt_connections_current 1070
telemt_connections_me_current 1070
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4575515
telemt_upstream_connect_attempt_total 48453
telemt_upstream_connect_success_total 48092
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 48444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_reconnect_attempts_total 48247
telemt_me_reconnect_success_total 1581
telemt_me_reader_eof_total 1238
telemt_me_idle_close_by_peer_total 1237
telemt_me_route_drop_no_conn_total 3990057
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5302373
telemt_me_endpoint_quarantine_total 663
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 767
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29664
telemt_desync_full_logged_total 10030
telemt_desync_suppressed_total 19634
telemt_desync_frames_bucket_total{bucket="1_2"} 5948
telemt_desync_frames_bucket_total{bucket="3_10"} 11726
telemt_desync_frames_bucket_total{bucket="gt_10"} 11990
telemt_pool_swap_total 108
telemt_pool_force_close_total 3305
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 342
telemt_me_draining_writers_reap_progress_total 35144
telemt_me_writer_removed_unexpected_total 1299
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3136
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33340
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 423
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31839
telemt_me_writer_teardown_success_total{mode="normal"} 36476
telemt_me_writer_teardown_noop_total 35151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71627
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.314766
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71627
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 342
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1405
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5295442
telemt_user_connections_current{user="hello"} 1070
telemt_user_octets_from_client{user="hello"} 113980284416 (106.15 GB)
telemt_user_octets_to_client{user="hello"} 2015158466378 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 82867.1 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1201654
telemt_connections_bad_total 24986
telemt_connections_current 1188
telemt_connections_me_current 1188
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 23529
telemt_upstream_connect_attempt_total 39792
telemt_upstream_connect_success_total 39675
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 39766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21091
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 639
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1778
telemt_me_reconnect_success_total 762
telemt_me_reader_eof_total 736
telemt_me_idle_close_by_peer_total 736
telemt_me_route_drop_no_conn_total 418812
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1064881
telemt_me_endpoint_quarantine_total 696
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 680
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 6166
telemt_desync_full_logged_total 1896
telemt_desync_suppressed_total 4270
telemt_desync_frames_bucket_total{bucket="1_2"} 1407
telemt_desync_frames_bucket_total{bucket="3_10"} 2429
telemt_desync_frames_bucket_total{bucket="gt_10"} 2330
telemt_pool_swap_total 88
telemt_pool_force_close_total 2263
telemt_me_writer_close_signal_drop_total 128
telemt_me_draining_writers_reap_progress_total 33035
telemt_me_writer_removed_unexpected_total 709
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2565
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31208
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30772
telemt_me_writer_teardown_success_total{mode="normal"} 33773
telemt_me_writer_teardown_noop_total 33038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66811
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.004163
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66811
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 128
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 647
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1061177
telemt_user_connections_current{user="hello"} 1188
telemt_user_octets_from_client{user="hello"} 19504811465 (18.17 GB)
telemt_user_octets_to_client{user="hello"} 453400073731 (422.26 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 165064.5 (45h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12815857
telemt_connections_bad_total 1489185
telemt_connections_current 1892
telemt_connections_me_current 1892
telemt_handshake_timeouts_total 361167
telemt_upstream_connect_attempt_total 62158
telemt_upstream_connect_success_total 61838
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 62031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31234
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2435
telemt_me_reconnect_success_total 1296
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1257
telemt_me_route_drop_no_conn_total 4361877
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9698955
telemt_me_endpoint_quarantine_total 1102
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1235
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
telemt_desync_total 39834
telemt_desync_full_logged_total 12998
telemt_desync_suppressed_total 26836
telemt_desync_frames_bucket_total{bucket="1_2"} 9496
telemt_desync_frames_bucket_total{bucket="3_10"} 14714
telemt_desync_frames_bucket_total{bucket="gt_10"} 15624
telemt_pool_swap_total 183
telemt_pool_force_close_total 5048
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 640
telemt_me_draining_writers_reap_progress_total 55920
telemt_me_writer_removed_unexpected_total 1211
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4613
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52554
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4874
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50872
telemt_me_writer_teardown_success_total{mode="normal"} 57167
telemt_me_writer_teardown_noop_total 55922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113089
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.089758
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113089
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 640
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1134
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9666927
telemt_user_connections_current{user="hello"} 1892
telemt_user_octets_from_client{user="hello"} 189219886848 (176.22 GB)
telemt_user_octets_to_client{user="hello"} 4263639534772 (3.88 TB)
telemt_user_unique_ips_current{user="hello"} 655
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 165061.2 (45h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11127408
telemt_connections_bad_total 1255554
telemt_connections_current 1609
telemt_connections_me_current 1609
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 290854
telemt_upstream_connect_attempt_total 88243
telemt_upstream_connect_success_total 87466
telemt_upstream_connect_fail_total 592
telemt_upstream_connect_attempts_per_request{bucket="1"} 88058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2054
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 592
telemt_me_reconnect_attempts_total 9513
telemt_me_reconnect_success_total 2224
telemt_me_reader_eof_total 2071
telemt_me_idle_close_by_peer_total 2071
telemt_me_seq_mismatch_total 77
telemt_me_route_drop_no_conn_total 5530021
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8601666
telemt_me_endpoint_quarantine_total 1270
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1235
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 39143
telemt_desync_full_logged_total 12648
telemt_desync_suppressed_total 26495
telemt_desync_frames_bucket_total{bucket="1_2"} 9745
telemt_desync_frames_bucket_total{bucket="3_10"} 14565
telemt_desync_frames_bucket_total{bucket="gt_10"} 14833
telemt_pool_swap_total 174
telemt_pool_force_close_total 4863
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 626
telemt_me_draining_writers_reap_progress_total 55539
telemt_me_writer_removed_unexpected_total 2098
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5828
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51881
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50676
telemt_me_writer_teardown_success_total{mode="normal"} 57709
telemt_me_writer_teardown_noop_total 55544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113253
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.013724
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113253
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 626
telemt_me_refill_failed_total 376
telemt_me_writer_restored_same_endpoint_total 1802
telemt_me_writer_restored_fallback_total 105
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 8607419
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 151406830981 (141.01 GB)
telemt_user_octets_to_client{user="hello"} 3307516459375 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 586
telemt_user_unique_ips_recent_window{user="hello"} 225
```
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

# Server Metrics 2026-03-22 03:21:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 22524.0 (6h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337096
telemt_connections_bad_total 22535
telemt_connections_current 906
telemt_connections_me_current 906
telemt_handshake_timeouts_total 19146
telemt_upstream_connect_attempt_total 9429
telemt_upstream_connect_success_total 9428
telemt_upstream_connect_attempts_per_request{bucket="1"} 9428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6057
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 274
telemt_me_reconnect_success_total 148
telemt_me_reader_eof_total 144
telemt_me_idle_close_by_peer_total 144
telemt_me_route_drop_no_conn_total 63697
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277729
telemt_me_endpoint_quarantine_total 178
telemt_me_single_endpoint_shadow_rotate_total 187
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
telemt_me_writers_active_current 45
telemt_desync_total 2477
telemt_desync_full_logged_total 680
telemt_desync_suppressed_total 1797
telemt_desync_frames_bucket_total{bucket="1_2"} 842
telemt_desync_frames_bucket_total{bucket="3_10"} 928
telemt_desync_frames_bucket_total{bucket="gt_10"} 707
telemt_pool_swap_total 24
telemt_pool_force_close_total 629
telemt_me_writer_close_signal_drop_total 44
telemt_me_draining_writers_reap_progress_total 8500
telemt_me_writer_removed_unexpected_total 143
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 573
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8061
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 624
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7871
telemt_me_writer_teardown_success_total{mode="normal"} 8634
telemt_me_writer_teardown_noop_total 8501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17135
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.978268
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17135
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 44
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 134
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 277225
telemt_user_connections_current{user="hello"} 906
telemt_user_octets_from_client{user="hello"} 3319235768 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 98819804772 (92.03 GB)
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 35889.9 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 820328
telemt_connections_bad_total 52717
telemt_connections_current 777
telemt_connections_me_current 777
telemt_handshake_timeouts_total 30127
telemt_upstream_connect_attempt_total 16746
telemt_upstream_connect_success_total 16488
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 16723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_reconnect_attempts_total 1381
telemt_me_reconnect_success_total 516
telemt_me_reader_eof_total 456
telemt_me_idle_close_by_peer_total 456
telemt_me_route_drop_no_conn_total 345861
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 648426
telemt_me_endpoint_quarantine_total 337
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 289
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 2792
telemt_desync_full_logged_total 1602
telemt_desync_suppressed_total 1190
telemt_desync_frames_bucket_total{bucket="1_2"} 590
telemt_desync_frames_bucket_total{bucket="3_10"} 1066
telemt_desync_frames_bucket_total{bucket="gt_10"} 1136
telemt_pool_swap_total 38
telemt_pool_force_close_total 1028
telemt_me_writer_close_signal_drop_total 72
telemt_me_draining_writers_reap_progress_total 14855
telemt_me_writer_removed_unexpected_total 433
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1236
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14062
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1006
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13827
telemt_me_writer_teardown_success_total{mode="normal"} 15298
telemt_me_writer_teardown_noop_total 14855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30153
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.780738
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30153
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 72
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 383
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 647495
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 10550651244 (9.83 GB)
telemt_user_octets_to_client{user="hello"} 229964963332 (214.17 GB)
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 110750.0 (30h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7826724
telemt_connections_bad_total 642799
telemt_connections_current 2161
telemt_connections_me_current 2161
telemt_handshake_timeouts_total 257013
telemt_upstream_connect_attempt_total 41214
telemt_upstream_connect_success_total 41138
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 41145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22367
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1599
telemt_me_reconnect_success_total 836
telemt_me_reader_eof_total 845
telemt_me_idle_close_by_peer_total 845
telemt_me_route_drop_no_conn_total 4548248
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6327496
telemt_me_endpoint_quarantine_total 712
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 828
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 18
telemt_desync_total 26624
telemt_desync_full_logged_total 8823
telemt_desync_suppressed_total 17801
telemt_desync_frames_bucket_total{bucket="1_2"} 5749
telemt_desync_frames_bucket_total{bucket="3_10"} 10394
telemt_desync_frames_bucket_total{bucket="gt_10"} 10481
telemt_pool_swap_total 119
telemt_pool_force_close_total 3936
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 607
telemt_me_draining_writers_reap_progress_total 37572
telemt_me_writer_removed_unexpected_total 813
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3139
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34781
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3697
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33636
telemt_me_writer_teardown_success_total{mode="normal"} 37920
telemt_me_writer_teardown_noop_total 37616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75536
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 160.796895
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75536
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 607
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 745
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6319556
telemt_user_connections_current{user="hello"} 2161
telemt_user_octets_from_client{user="hello"} 107494147832 (100.11 GB)
telemt_user_octets_to_client{user="hello"} 2111858959540 (1.92 TB)
telemt_user_unique_ips_current{user="hello"} 1036
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 110751.2 (30h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6474909
telemt_connections_bad_total 589915
telemt_connections_current 1789
telemt_connections_me_current 1789
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 214515
telemt_upstream_connect_attempt_total 45222
telemt_upstream_connect_success_total 44830
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 45024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1955
telemt_me_reconnect_success_total 886
telemt_me_reader_eof_total 858
telemt_me_idle_close_by_peer_total 858
telemt_me_route_drop_no_conn_total 2268815
telemt_me_route_drop_channel_closed_total 265
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4828266
telemt_me_endpoint_quarantine_total 693
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 851
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 19
telemt_desync_total 22779
telemt_desync_full_logged_total 7766
telemt_desync_suppressed_total 15013
telemt_desync_frames_bucket_total{bucket="1_2"} 5477
telemt_desync_frames_bucket_total{bucket="3_10"} 8855
telemt_desync_frames_bucket_total{bucket="gt_10"} 8447
telemt_pool_swap_total 120
telemt_pool_force_close_total 3571
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 368
telemt_me_draining_writers_reap_progress_total 36101
telemt_me_writer_removed_unexpected_total 842
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2995
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33886
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3358
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32530
telemt_me_writer_teardown_success_total{mode="normal"} 36881
telemt_me_writer_teardown_noop_total 36107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72988
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.454626
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72988
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 368
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 775
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4750356
telemt_user_connections_current{user="hello"} 1789
telemt_user_octets_from_client{user="hello"} 141099015213 (131.41 GB)
telemt_user_octets_to_client{user="hello"} 2249421281715 (2.05 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 885
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 110715.3 (30h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6343035
telemt_connections_bad_total 549777
telemt_connections_current 1489
telemt_connections_me_current 1489
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 205965
telemt_upstream_connect_attempt_total 51306
telemt_upstream_connect_success_total 50926
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 51062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 519
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1082
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2087
telemt_me_reconnect_success_total 927
telemt_me_reader_eof_total 875
telemt_me_idle_close_by_peer_total 875
telemt_me_route_drop_no_conn_total 2162619
telemt_me_route_drop_channel_closed_total 125
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4713761
telemt_me_endpoint_quarantine_total 777
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 825
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
telemt_desync_total 22697
telemt_desync_full_logged_total 7640
telemt_desync_suppressed_total 15057
telemt_desync_frames_bucket_total{bucket="1_2"} 5545
telemt_desync_frames_bucket_total{bucket="3_10"} 8696
telemt_desync_frames_bucket_total{bucket="gt_10"} 8456
telemt_pool_swap_total 119
telemt_pool_force_close_total 3455
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 37185
telemt_me_writer_removed_unexpected_total 844
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3079
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34967
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3240
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33730
telemt_me_writer_teardown_success_total{mode="normal"} 38046
telemt_me_writer_teardown_noop_total 37197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75243
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.835754
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75243
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 805
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 4709251
telemt_user_connections_current{user="hello"} 1489
telemt_user_octets_from_client{user="hello"} 134584684275 (125.34 GB)
telemt_user_octets_to_client{user="hello"} 2160995903799 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 737
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 110754.7 (30h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20536472
telemt_connections_bad_total 1660163
telemt_connections_current 2416
telemt_connections_me_current 2416
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 615889
telemt_upstream_connect_attempt_total 200140
telemt_upstream_connect_success_total 182022
telemt_upstream_connect_fail_total 16344
telemt_upstream_connect_attempts_per_request{bucket="1"} 198366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43267
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8933
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16344
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65030
telemt_me_reconnect_success_total 2344
telemt_me_reader_eof_total 1474
telemt_me_idle_close_by_peer_total 1473
telemt_me_route_drop_no_conn_total 39529198
telemt_me_route_drop_channel_closed_total 126
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16571535
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 864
telemt_me_single_endpoint_outage_enter_total 135
telemt_me_single_endpoint_outage_exit_total 135
telemt_me_single_endpoint_outage_reconnect_attempt_total 285
telemt_me_single_endpoint_outage_reconnect_success_total 70
telemt_me_single_endpoint_quarantine_bypass_total 285
telemt_me_single_endpoint_shadow_rotate_total 864
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 19
telemt_desync_total 32113
telemt_desync_full_logged_total 9655
telemt_desync_suppressed_total 22458
telemt_desync_frames_bucket_total{bucket="1_2"} 6954
telemt_desync_frames_bucket_total{bucket="3_10"} 14251
telemt_desync_frames_bucket_total{bucket="gt_10"} 10908
telemt_pool_swap_total 114
telemt_pool_force_close_total 3686
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 806
telemt_me_draining_writers_reap_progress_total 34725
telemt_me_writer_removed_unexpected_total 2172
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4663
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31975
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3161
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 525
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31039
telemt_me_writer_teardown_success_total{mode="normal"} 36638
telemt_me_writer_teardown_noop_total 34752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71390
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 215.249623
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71390
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 806
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1605
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 546
telemt_user_connections_total{user="hello"} 16704624
telemt_user_connections_current{user="hello"} 2416
telemt_user_octets_from_client{user="hello"} 226467119248 (210.91 GB)
telemt_user_octets_to_client{user="hello"} 1227110826689 (1.12 TB)
telemt_user_msgs_from_client{user="hello"} 395497
telemt_user_msgs_to_client{user="hello"} 785476
telemt_user_unique_ips_current{user="hello"} 1129
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 110722.3 (30h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6097137
telemt_connections_bad_total 581894
telemt_connections_current 1727
telemt_connections_me_current 1727
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 128448
telemt_upstream_connect_attempt_total 60005
telemt_upstream_connect_success_total 59313
telemt_upstream_connect_fail_total 591
telemt_upstream_connect_attempts_per_request{bucket="1"} 59904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 591
telemt_me_reconnect_attempts_total 69730
telemt_me_reconnect_success_total 1813
telemt_me_reader_eof_total 1596
telemt_me_idle_close_by_peer_total 1595
telemt_me_route_drop_no_conn_total 2398753
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4744428
telemt_me_endpoint_quarantine_total 749
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 838
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 23615
telemt_desync_full_logged_total 8309
telemt_desync_suppressed_total 15306
telemt_desync_frames_bucket_total{bucket="1_2"} 4521
telemt_desync_frames_bucket_total{bucket="3_10"} 9149
telemt_desync_frames_bucket_total{bucket="gt_10"} 9945
telemt_pool_swap_total 114
telemt_pool_force_close_total 3268
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 39087
telemt_me_writer_removed_unexpected_total 1633
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3997
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36755
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35819
telemt_me_writer_teardown_success_total{mode="normal"} 40752
telemt_me_writer_teardown_noop_total 39088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79840
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.136435
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79840
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 4209
telemt_me_writer_restored_same_endpoint_total 1522
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 4737149
telemt_user_connections_current{user="hello"} 1727
telemt_user_octets_from_client{user="hello"} 125347618772 (116.74 GB)
telemt_user_octets_to_client{user="hello"} 1932871435562 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 867
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 47558.2 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4018500
telemt_connections_bad_total 158482
telemt_connections_current 1403
telemt_connections_me_current 1403
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1627874
telemt_upstream_connect_attempt_total 28719
telemt_upstream_connect_success_total 28537
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 28712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_reconnect_attempts_total 45837
telemt_me_reconnect_success_total 982
telemt_me_reader_eof_total 666
telemt_me_idle_close_by_peer_total 666
telemt_me_route_drop_no_conn_total 1030442
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1967542
telemt_me_endpoint_quarantine_total 355
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 366
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10603
telemt_desync_full_logged_total 3667
telemt_desync_suppressed_total 6936
telemt_desync_frames_bucket_total{bucket="1_2"} 1917
telemt_desync_frames_bucket_total{bucket="3_10"} 4067
telemt_desync_frames_bucket_total{bucket="gt_10"} 4619
telemt_pool_swap_total 51
telemt_pool_force_close_total 1526
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 17651
telemt_me_writer_removed_unexpected_total 739
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1571
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16846
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1320
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16125
telemt_me_writer_teardown_success_total{mode="normal"} 18417
telemt_me_writer_teardown_noop_total 17653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.494627
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 880
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1971085
telemt_user_connections_current{user="hello"} 1403
telemt_user_octets_from_client{user="hello"} 54802794584 (51.04 GB)
telemt_user_octets_to_client{user="hello"} 835273475898 (777.91 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 749
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 28528.9 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207051
telemt_connections_bad_total 1759
telemt_connections_current 369
telemt_connections_me_current 369
telemt_handshake_timeouts_total 5643
telemt_upstream_connect_attempt_total 13733
telemt_upstream_connect_success_total 13701
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 298
telemt_me_reconnect_success_total 175
telemt_me_reader_eof_total 180
telemt_me_idle_close_by_peer_total 180
telemt_me_route_drop_no_conn_total 57516
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182825
telemt_me_endpoint_quarantine_total 283
telemt_me_single_endpoint_shadow_rotate_total 248
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_me_writers_active_current 44
telemt_desync_total 1060
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 789
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 397
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 31
telemt_pool_force_close_total 692
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 12411
telemt_me_writer_removed_unexpected_total 173
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 799
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11792
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 690
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11719
telemt_me_writer_teardown_success_total{mode="normal"} 12591
telemt_me_writer_teardown_noop_total 12411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25002
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.048563
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25002
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 159
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 182503
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 3248171736 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 114213071260 (106.37 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 110726.9 (30h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7414820
telemt_connections_bad_total 746687
telemt_connections_current 1758
telemt_connections_me_current 1758
telemt_handshake_timeouts_total 210957
telemt_upstream_connect_attempt_total 43465
telemt_upstream_connect_success_total 43306
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 43428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_reconnect_attempts_total 1594
telemt_me_reconnect_success_total 858
telemt_me_reader_eof_total 843
telemt_me_idle_close_by_peer_total 843
telemt_me_route_drop_no_conn_total 2137605
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5531905
telemt_me_endpoint_quarantine_total 779
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 853
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 2
telemt_desync_total 21727
telemt_desync_full_logged_total 7115
telemt_desync_suppressed_total 14612
telemt_desync_frames_bucket_total{bucket="1_2"} 5460
telemt_desync_frames_bucket_total{bucket="3_10"} 7870
telemt_desync_frames_bucket_total{bucket="gt_10"} 8397
telemt_pool_swap_total 122
telemt_pool_force_close_total 3260
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 392
telemt_me_draining_writers_reap_progress_total 39211
telemt_me_writer_removed_unexpected_total 812
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3063
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36981
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3172
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35951
telemt_me_writer_teardown_success_total{mode="normal"} 40044
telemt_me_writer_teardown_noop_total 39213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79257
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.680188
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79257
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 392
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 767
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 5506875
telemt_user_connections_current{user="hello"} 1758
telemt_user_octets_from_client{user="hello"} 110297033680 (102.72 GB)
telemt_user_octets_to_client{user="hello"} 2566586358268 (2.33 TB)
telemt_user_unique_ips_current{user="hello"} 840
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 110723.5 (30h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6413067
telemt_connections_bad_total 632773
telemt_connections_current 1830
telemt_connections_me_current 1830
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 174245
telemt_upstream_connect_attempt_total 59273
telemt_upstream_connect_success_total 58828
telemt_upstream_connect_fail_total 386
telemt_upstream_connect_attempts_per_request{bucket="1"} 59214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23485
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 386
telemt_me_reconnect_attempts_total 5598
telemt_me_reconnect_success_total 1197
telemt_me_reader_eof_total 1082
telemt_me_idle_close_by_peer_total 1082
telemt_me_seq_mismatch_total 50
telemt_me_route_drop_no_conn_total 2190796
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4898783
telemt_me_endpoint_quarantine_total 874
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 847
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
telemt_me_writers_active_current 43
telemt_desync_total 20338
telemt_desync_full_logged_total 6780
telemt_desync_suppressed_total 13558
telemt_desync_frames_bucket_total{bucket="1_2"} 5209
telemt_desync_frames_bucket_total{bucket="3_10"} 7413
telemt_desync_frames_bucket_total{bucket="gt_10"} 7716
telemt_pool_swap_total 120
telemt_pool_force_close_total 3219
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 37771
telemt_me_writer_removed_unexpected_total 1093
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3603
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35315
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2996
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34552
telemt_me_writer_teardown_success_total{mode="normal"} 38918
telemt_me_writer_teardown_noop_total 37775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76693
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.100774
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76693
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 936
telemt_me_writer_restored_fallback_total 67
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4901735
telemt_user_connections_current{user="hello"} 1830
telemt_user_octets_from_client{user="hello"} 92644776269 (86.28 GB)
telemt_user_octets_to_client{user="hello"} 2095003770460 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 809
telemt_user_unique_ips_recent_window{user="hello"} 161
```
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

# Server Metrics 2026-03-22 00:08:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 10904.7 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168189
telemt_connections_bad_total 11315
telemt_connections_current 687
telemt_connections_me_current 687
telemt_handshake_timeouts_total 9396
telemt_upstream_connect_attempt_total 4435
telemt_upstream_connect_success_total 4434
telemt_upstream_connect_attempts_per_request{bucket="1"} 4434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2768
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 104
telemt_me_reconnect_success_total 69
telemt_me_reader_eof_total 70
telemt_me_idle_close_by_peer_total 70
telemt_me_route_drop_no_conn_total 34653
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137956
telemt_me_endpoint_quarantine_total 74
telemt_me_single_endpoint_shadow_rotate_total 94
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
telemt_me_writers_active_current 43
telemt_desync_total 901
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 632
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 389
telemt_pool_swap_total 12
telemt_pool_force_close_total 299
telemt_me_writer_close_signal_drop_total 19
telemt_me_draining_writers_reap_progress_total 3942
telemt_me_writer_removed_unexpected_total 66
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 290
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3706
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3643
telemt_me_writer_teardown_success_total{mode="normal"} 3996
telemt_me_writer_teardown_noop_total 3942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7938
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.336882
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7938
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 19
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 64
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 137783
telemt_user_connections_current{user="hello"} 687
telemt_user_octets_from_client{user="hello"} 1632311944 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 49143512648 (45.77 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 24270.0 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 679851
telemt_connections_bad_total 37195
telemt_connections_current 740
telemt_connections_me_current 740
telemt_handshake_timeouts_total 25797
telemt_upstream_connect_attempt_total 10361
telemt_upstream_connect_success_total 10179
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 10343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_reconnect_attempts_total 859
telemt_me_reconnect_success_total 312
telemt_me_reader_eof_total 269
telemt_me_idle_close_by_peer_total 269
telemt_me_route_drop_no_conn_total 327422
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 550483
telemt_me_endpoint_quarantine_total 212
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 2403
telemt_desync_full_logged_total 1378
telemt_desync_suppressed_total 1025
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 900
telemt_desync_frames_bucket_total{bucket="gt_10"} 989
telemt_pool_swap_total 26
telemt_pool_force_close_total 726
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 9123
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 799
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8580
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 719
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8397
telemt_me_writer_teardown_success_total{mode="normal"} 9379
telemt_me_writer_teardown_noop_total 9123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18502
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.381109
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18502
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 217
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 549730
telemt_user_connections_current{user="hello"} 740
telemt_user_octets_from_client{user="hello"} 9192372988 (8.56 GB)
telemt_user_octets_to_client{user="hello"} 191357849996 (178.22 GB)
telemt_user_unique_ips_current{user="hello"} 440
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 99130.0 (27h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7464511
telemt_connections_bad_total 593650
telemt_connections_current 1972
telemt_connections_me_current 1972
telemt_handshake_timeouts_total 242599
telemt_upstream_connect_attempt_total 36003
telemt_upstream_connect_success_total 35933
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 35940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19509
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1493
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 755
telemt_me_idle_close_by_peer_total 755
telemt_me_route_drop_no_conn_total 4501729
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6084197
telemt_me_endpoint_quarantine_total 630
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 735
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
telemt_desync_total 25825
telemt_desync_full_logged_total 8536
telemt_desync_suppressed_total 17289
telemt_desync_frames_bucket_total{bucket="1_2"} 5557
telemt_desync_frames_bucket_total{bucket="3_10"} 10076
telemt_desync_frames_bucket_total{bucket="gt_10"} 10192
telemt_pool_swap_total 107
telemt_pool_force_close_total 3583
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 575
telemt_me_draining_writers_reap_progress_total 32800
telemt_me_writer_removed_unexpected_total 726
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2775
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30309
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3344
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29217
telemt_me_writer_teardown_success_total{mode="normal"} 33084
telemt_me_writer_teardown_noop_total 32844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65928
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 153.624050
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65928
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 575
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 666
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6076619
telemt_user_connections_current{user="hello"} 1972
telemt_user_octets_from_client{user="hello"} 104118057312 (96.97 GB)
telemt_user_octets_to_client{user="hello"} 2000515204144 (1.82 TB)
telemt_user_unique_ips_current{user="hello"} 959
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 99131.3 (27h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6139258
telemt_connections_bad_total 578550
telemt_connections_current 1460
telemt_connections_me_current 1460
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 202582
telemt_upstream_connect_attempt_total 39895
telemt_upstream_connect_success_total 39530
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 39714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 552
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1812
telemt_me_reconnect_success_total 776
telemt_me_reader_eof_total 753
telemt_me_idle_close_by_peer_total 753
telemt_me_route_drop_no_conn_total 2182938
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4601183
telemt_me_endpoint_quarantine_total 605
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 755
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
telemt_me_writers_active_current 50
telemt_me_writers_warm_current 33
telemt_desync_total 22127
telemt_desync_full_logged_total 7484
telemt_desync_suppressed_total 14643
telemt_desync_frames_bucket_total{bucket="1_2"} 5329
telemt_desync_frames_bucket_total{bucket="3_10"} 8583
telemt_desync_frames_bucket_total{bucket="gt_10"} 8215
telemt_pool_swap_total 108
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 31263
telemt_me_writer_removed_unexpected_total 728
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2651
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29275
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3047
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28017
telemt_me_writer_teardown_success_total{mode="normal"} 31926
telemt_me_writer_teardown_noop_total 31269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63195
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.990031
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63195
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 672
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4540936
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 138202058441 (128.71 GB)
telemt_user_octets_to_client{user="hello"} 2125371809419 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 710
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 99095.7 (27h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6050908
telemt_connections_bad_total 540350
telemt_connections_current 1527
telemt_connections_me_current 1527
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 193813
telemt_upstream_connect_attempt_total 46365
telemt_upstream_connect_success_total 46055
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 46190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20641
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1814
telemt_me_reconnect_success_total 826
telemt_me_reader_eof_total 774
telemt_me_idle_close_by_peer_total 774
telemt_me_route_drop_no_conn_total 2107100
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4516896
telemt_me_endpoint_quarantine_total 673
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 739
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
telemt_me_writers_active_current 43
telemt_desync_total 21932
telemt_desync_full_logged_total 7312
telemt_desync_suppressed_total 14620
telemt_desync_frames_bucket_total{bucket="1_2"} 5366
telemt_desync_frames_bucket_total{bucket="3_10"} 8395
telemt_desync_frames_bucket_total{bucket="gt_10"} 8171
telemt_pool_swap_total 107
telemt_pool_force_close_total 3123
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 32784
telemt_me_writer_removed_unexpected_total 740
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2743
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30790
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2908
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29661
telemt_me_writer_teardown_success_total{mode="normal"} 33533
telemt_me_writer_teardown_noop_total 32795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66328
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.462173
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66328
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 716
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4518032
telemt_user_connections_current{user="hello"} 1527
telemt_user_octets_from_client{user="hello"} 131789753803 (122.74 GB)
telemt_user_octets_to_client{user="hello"} 2071704356527 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 798
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 99134.6 (27h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20006510
telemt_connections_bad_total 1484366
telemt_connections_current 2216
telemt_connections_me_current 2216
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 578899
telemt_upstream_connect_attempt_total 189482
telemt_upstream_connect_success_total 171845
telemt_upstream_connect_fail_total 16038
telemt_upstream_connect_attempts_per_request{bucket="1"} 187883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8884
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16038
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64361
telemt_me_reconnect_success_total 2166
telemt_me_reader_eof_total 1353
telemt_me_idle_close_by_peer_total 1352
telemt_me_route_drop_no_conn_total 39454160
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16275818
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 766
telemt_me_single_endpoint_outage_enter_total 123
telemt_me_single_endpoint_outage_exit_total 123
telemt_me_single_endpoint_outage_reconnect_attempt_total 259
telemt_me_single_endpoint_outage_reconnect_success_total 62
telemt_me_single_endpoint_quarantine_bypass_total 259
telemt_me_single_endpoint_shadow_rotate_total 774
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 31337
telemt_desync_full_logged_total 9330
telemt_desync_suppressed_total 22007
telemt_desync_frames_bucket_total{bucket="1_2"} 6831
telemt_desync_frames_bucket_total{bucket="3_10"} 13875
telemt_desync_frames_bucket_total{bucket="gt_10"} 10631
telemt_pool_swap_total 102
telemt_pool_force_close_total 3346
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 760
telemt_me_draining_writers_reap_progress_total 30789
telemt_me_writer_removed_unexpected_total 2012
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4220
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28317
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2830
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27443
telemt_me_writer_teardown_success_total{mode="normal"} 32537
telemt_me_writer_teardown_noop_total 30815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63352
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 211.559897
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63352
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 760
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1499
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 16403723
telemt_user_connections_current{user="hello"} 2216
telemt_user_octets_from_client{user="hello"} 188622301656 (175.67 GB)
telemt_user_octets_to_client{user="hello"} 1123651222410 (1.02 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 1026
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 99102.1 (27h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5844302
telemt_connections_bad_total 552016
telemt_connections_current 1541
telemt_connections_me_current 1541
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 120849
telemt_upstream_connect_attempt_total 54544
telemt_upstream_connect_success_total 53919
telemt_upstream_connect_fail_total 534
telemt_upstream_connect_attempts_per_request{bucket="1"} 54453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21541
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 534
telemt_me_reconnect_attempts_total 68094
telemt_me_reconnect_success_total 1693
telemt_me_reader_eof_total 1470
telemt_me_idle_close_by_peer_total 1469
telemt_me_route_drop_no_conn_total 2360000
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4554052
telemt_me_endpoint_quarantine_total 656
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 740
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 38
telemt_desync_total 22999
telemt_desync_full_logged_total 8060
telemt_desync_suppressed_total 14939
telemt_desync_frames_bucket_total{bucket="1_2"} 4360
telemt_desync_frames_bucket_total{bucket="3_10"} 8911
telemt_desync_frames_bucket_total{bucket="gt_10"} 9728
telemt_pool_swap_total 101
telemt_pool_force_close_total 2974
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 34189
telemt_me_writer_removed_unexpected_total 1515
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3629
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32099
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2573
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31215
telemt_me_writer_teardown_success_total{mode="normal"} 35728
telemt_me_writer_teardown_noop_total 34190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69918
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.928747
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69918
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 1429
telemt_me_writer_restored_fallback_total 29
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 4547159
telemt_user_connections_current{user="hello"} 1541
telemt_user_octets_from_client{user="hello"} 122053742868 (113.67 GB)
telemt_user_octets_to_client{user="hello"} 1858518736382 (1.69 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 756
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 35937.9 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3714723
telemt_connections_bad_total 131769
telemt_connections_current 1251
telemt_connections_me_current 1251
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1543091
telemt_upstream_connect_attempt_total 22764
telemt_upstream_connect_success_total 22620
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 22757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 45589
telemt_me_reconnect_success_total 888
telemt_me_reader_eof_total 561
telemt_me_idle_close_by_peer_total 561
telemt_me_route_drop_no_conn_total 997567
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1798294
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 269
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9983
telemt_desync_full_logged_total 3422
telemt_desync_suppressed_total 6561
telemt_desync_frames_bucket_total{bucket="1_2"} 1765
telemt_desync_frames_bucket_total{bucket="3_10"} 3820
telemt_desync_frames_bucket_total{bucket="gt_10"} 4398
telemt_pool_swap_total 38
telemt_pool_force_close_total 1246
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 12216
telemt_me_writer_removed_unexpected_total 641
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1304
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11573
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1040
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10970
telemt_me_writer_teardown_success_total{mode="normal"} 12877
telemt_me_writer_teardown_noop_total 12218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25095
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.089377
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25095
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 2597
telemt_me_writer_restored_same_endpoint_total 797
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1802044
telemt_user_connections_current{user="hello"} 1251
telemt_user_octets_from_client{user="hello"} 52667166548 (49.05 GB)
telemt_user_octets_to_client{user="hello"} 771973246290 (718.96 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 637
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 16908.9 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161431
telemt_connections_bad_total 1398
telemt_connections_current 301
telemt_connections_me_current 301
telemt_handshake_timeouts_total 3840
telemt_upstream_connect_attempt_total 7752
telemt_upstream_connect_success_total 7732
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 7751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 164
telemt_me_reconnect_success_total 102
telemt_me_reader_eof_total 102
telemt_me_idle_close_by_peer_total 102
telemt_me_route_drop_no_conn_total 45828
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141973
telemt_me_endpoint_quarantine_total 152
telemt_me_single_endpoint_shadow_rotate_total 148
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
telemt_me_writers_active_current 44
telemt_desync_total 973
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 731
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 18
telemt_pool_force_close_total 421
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 6946
telemt_me_writer_removed_unexpected_total 100
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 457
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6591
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6525
telemt_me_writer_teardown_success_total{mode="normal"} 7048
telemt_me_writer_teardown_noop_total 6946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13994
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.787237
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13994
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 94
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 141710
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 2603813920 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 81773138588 (76.16 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 99106.5 (27h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7047301
telemt_connections_bad_total 714239
telemt_connections_current 1701
telemt_connections_me_current 1701
telemt_handshake_timeouts_total 200898
telemt_upstream_connect_attempt_total 37996
telemt_upstream_connect_success_total 37849
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 37959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 1497
telemt_me_reconnect_success_total 784
telemt_me_reader_eof_total 762
telemt_me_idle_close_by_peer_total 762
telemt_me_route_drop_no_conn_total 2098564
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5318988
telemt_me_endpoint_quarantine_total 685
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 757
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
telemt_desync_total 20546
telemt_desync_full_logged_total 6859
telemt_desync_suppressed_total 13687
telemt_desync_frames_bucket_total{bucket="1_2"} 5010
telemt_desync_frames_bucket_total{bucket="3_10"} 7452
telemt_desync_frames_bucket_total{bucket="gt_10"} 8084
telemt_pool_swap_total 110
telemt_pool_force_close_total 2968
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 370
telemt_me_draining_writers_reap_progress_total 34165
telemt_me_writer_removed_unexpected_total 737
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2749
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32168
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2880
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31197
telemt_me_writer_teardown_success_total{mode="normal"} 34917
telemt_me_writer_teardown_noop_total 34167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69084
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.563919
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69084
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 370
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 699
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 5294195
telemt_user_connections_current{user="hello"} 1701
telemt_user_octets_from_client{user="hello"} 107741537476 (100.34 GB)
telemt_user_octets_to_client{user="hello"} 2487446676840 (2.26 TB)
telemt_user_unique_ips_current{user="hello"} 771
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 99103.1 (27h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6035338
telemt_connections_bad_total 591941
telemt_connections_current 1656
telemt_connections_me_current 1656
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 167418
telemt_upstream_connect_attempt_total 53962
telemt_upstream_connect_success_total 53552
telemt_upstream_connect_fail_total 350
telemt_upstream_connect_attempts_per_request{bucket="1"} 53902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20780
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 350
telemt_me_reconnect_attempts_total 5334
telemt_me_reconnect_success_total 1092
telemt_me_reader_eof_total 970
telemt_me_idle_close_by_peer_total 970
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 2152385
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4689541
telemt_me_endpoint_quarantine_total 782
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 753
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_me_writers_warm_current 39
telemt_desync_total 19328
telemt_desync_full_logged_total 6493
telemt_desync_suppressed_total 12835
telemt_desync_frames_bucket_total{bucket="1_2"} 4864
telemt_desync_frames_bucket_total{bucket="3_10"} 7028
telemt_desync_frames_bucket_total{bucket="gt_10"} 7436
telemt_pool_swap_total 107
telemt_pool_force_close_total 2933
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 32908
telemt_me_writer_removed_unexpected_total 983
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3232
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30703
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2710
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29975
telemt_me_writer_teardown_success_total{mode="normal"} 33935
telemt_me_writer_teardown_noop_total 32912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66847
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.896354
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66847
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 245
telemt_me_writer_restored_same_endpoint_total 847
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 4692810
telemt_user_connections_current{user="hello"} 1656
telemt_user_octets_from_client{user="hello"} 88785998821 (82.69 GB)
telemt_user_octets_to_client{user="hello"} 2013533288196 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 770
telemt_user_unique_ips_recent_window{user="hello"} 142
```
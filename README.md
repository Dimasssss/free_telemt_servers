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

# Server Metrics 2026-03-22 15:13:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 65209.1 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2262478
telemt_connections_bad_total 120234
telemt_connections_current 1842
telemt_connections_me_current 1842
telemt_handshake_timeouts_total 85147
telemt_upstream_connect_attempt_total 24208
telemt_upstream_connect_success_total 24207
telemt_upstream_connect_attempts_per_request{bucket="1"} 24207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1001
telemt_me_reconnect_success_total 409
telemt_me_reader_eof_total 412
telemt_me_idle_close_by_peer_total 412
telemt_me_route_drop_no_conn_total 1843278
telemt_me_route_drop_channel_closed_total 745
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1921217
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 514
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 9538
telemt_desync_full_logged_total 2948
telemt_desync_suppressed_total 6590
telemt_desync_frames_bucket_total{bucket="1_2"} 2610
telemt_desync_frames_bucket_total{bucket="3_10"} 3582
telemt_desync_frames_bucket_total{bucket="gt_10"} 3346
telemt_pool_swap_total 72
telemt_pool_force_close_total 2217
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 404
telemt_me_draining_writers_reap_progress_total 22119
telemt_me_writer_removed_unexpected_total 399
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1598
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20721
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2170
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19902
telemt_me_writer_teardown_success_total{mode="normal"} 22319
telemt_me_writer_teardown_noop_total 22124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44443
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 193.899681
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44443
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 404
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 360
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1918075
telemt_user_connections_current{user="hello"} 1842
telemt_user_octets_from_client{user="hello"} 28974687888 (26.98 GB)
telemt_user_octets_to_client{user="hello"} 517325291596 (481.80 GB)
telemt_user_unique_ips_current{user="hello"} 656
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 78575.0 (21h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3501837
telemt_connections_bad_total 314059
telemt_connections_current 653
telemt_connections_me_current 653
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 82862
telemt_upstream_connect_attempt_total 49874
telemt_upstream_connect_success_total 49272
telemt_upstream_connect_fail_total 530
telemt_upstream_connect_attempts_per_request{bucket="1"} 49802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 530
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5676
telemt_me_reconnect_success_total 1948
telemt_me_reader_eof_total 1875
telemt_me_idle_close_by_peer_total 1875
telemt_me_route_drop_no_conn_total 3503693
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2779393
telemt_me_endpoint_quarantine_total 641
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 610
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
telemt_me_writers_active_current 43
telemt_desync_total 10698
telemt_desync_full_logged_total 5930
telemt_desync_suppressed_total 4768
telemt_desync_frames_bucket_total{bucket="1_2"} 2514
telemt_desync_frames_bucket_total{bucket="3_10"} 4218
telemt_desync_frames_bucket_total{bucket="gt_10"} 3966
telemt_pool_swap_total 75
telemt_pool_force_close_total 2228
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 186
telemt_me_draining_writers_reap_progress_total 31222
telemt_me_writer_removed_unexpected_total 1831
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3621
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29435
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 318
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28994
telemt_me_writer_teardown_success_total{mode="normal"} 33056
telemt_me_writer_teardown_noop_total 31222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64278
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.567184
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64278
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 186
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1658
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 2790751
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 34010414471 (31.67 GB)
telemt_user_octets_to_client{user="hello"} 604261706834 (562.76 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 153435.0 (42h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15084199
telemt_connections_bad_total 1377211
telemt_connections_current 2255
telemt_connections_me_current 2255
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 366239
telemt_upstream_connect_attempt_total 69728
telemt_upstream_connect_success_total 69633
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 69650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32757
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1659
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2562
telemt_me_reconnect_success_total 1326
telemt_me_reader_eof_total 1263
telemt_me_idle_close_by_peer_total 1262
telemt_me_route_drop_no_conn_total 13723637
telemt_me_route_drop_channel_closed_total 134
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12076541
telemt_me_endpoint_quarantine_total 971
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1143
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
telemt_desync_total 48574
telemt_desync_full_logged_total 15275
telemt_desync_suppressed_total 33299
telemt_desync_frames_bucket_total{bucket="1_2"} 10936
telemt_desync_frames_bucket_total{bucket="3_10"} 19006
telemt_desync_frames_bucket_total{bucket="gt_10"} 18632
telemt_pool_swap_total 165
telemt_pool_force_close_total 5630
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 920
telemt_me_draining_writers_reap_progress_total 50486
telemt_me_writer_removed_unexpected_total 1219
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4399
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46611
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5174
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44856
telemt_me_writer_teardown_success_total{mode="normal"} 51010
telemt_me_writer_teardown_noop_total 50536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101546
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 290.435576
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101546
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 920
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 1138
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 12078040
telemt_user_connections_current{user="hello"} 2255
telemt_user_octets_from_client{user="hello"} 169046607945 (157.44 GB)
telemt_user_octets_to_client{user="hello"} 3096584604155 (2.82 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 938
telemt_user_unique_ips_recent_window{user="hello"} 290
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 153436.6 (42h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10877063
telemt_connections_bad_total 1047919
telemt_connections_current 1657
telemt_connections_me_current 1657
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 321814
telemt_upstream_connect_attempt_total 81918
telemt_upstream_connect_success_total 80768
telemt_upstream_connect_fail_total 826
telemt_upstream_connect_attempts_per_request{bucket="1"} 81594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32656
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 826
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3855
telemt_me_reconnect_success_total 1550
telemt_me_reader_eof_total 1425
telemt_me_idle_close_by_peer_total 1425
telemt_me_route_drop_no_conn_total 4316677
telemt_me_route_drop_channel_closed_total 476
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8120214
telemt_me_endpoint_quarantine_total 962
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1163
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 36044
telemt_desync_full_logged_total 12105
telemt_desync_suppressed_total 23939
telemt_desync_frames_bucket_total{bucket="1_2"} 8851
telemt_desync_frames_bucket_total{bucket="3_10"} 13869
telemt_desync_frames_bucket_total{bucket="gt_10"} 13324
telemt_pool_swap_total 163
telemt_pool_force_close_total 5067
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 649
telemt_me_draining_writers_reap_progress_total 48801
telemt_me_writer_removed_unexpected_total 1457
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4496
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45619
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4597
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43734
telemt_me_writer_teardown_success_total{mode="normal"} 50115
telemt_me_writer_teardown_noop_total 48817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98932
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 98.838739
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98932
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 649
telemt_me_refill_failed_total 125
telemt_me_writer_restored_same_endpoint_total 1321
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 8059095
telemt_user_connections_current{user="hello"} 1657
telemt_user_octets_from_client{user="hello"} 202569203873 (188.66 GB)
telemt_user_octets_to_client{user="hello"} 3632492203986 (3.30 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 732
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 153400.3 (42h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10318169
telemt_connections_bad_total 882544
telemt_connections_current 1323
telemt_connections_me_current 1323
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 329229
telemt_upstream_connect_attempt_total 67179
telemt_upstream_connect_success_total 66254
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 66436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31219
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2050
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4612
telemt_me_reconnect_success_total 1854
telemt_me_reader_eof_total 1614
telemt_me_idle_close_by_peer_total 1613
telemt_me_route_drop_no_conn_total 5091155
telemt_me_route_drop_channel_closed_total 352
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7790504
telemt_me_endpoint_quarantine_total 1056
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1126
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
telemt_me_writers_active_current 40
telemt_desync_total 35704
telemt_desync_full_logged_total 11830
telemt_desync_suppressed_total 23874
telemt_desync_frames_bucket_total{bucket="1_2"} 9036
telemt_desync_frames_bucket_total{bucket="3_10"} 13642
telemt_desync_frames_bucket_total{bucket="gt_10"} 13026
telemt_pool_swap_total 160
telemt_pool_force_close_total 5021
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 681
telemt_me_draining_writers_reap_progress_total 49268
telemt_me_writer_removed_unexpected_total 1754
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4946
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45988
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4484
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 537
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44247
telemt_me_writer_teardown_success_total{mode="normal"} 50934
telemt_me_writer_teardown_noop_total 49339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100273
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3169.902506
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100273
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 681
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1610
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 7783634
telemt_user_connections_current{user="hello"} 1323
telemt_user_octets_from_client{user="hello"} 180004205937 (167.64 GB)
telemt_user_octets_to_client{user="hello"} 3231992375113 (2.94 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 556
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 23680.9 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9902035
telemt_connections_bad_total 606810
telemt_connections_current 2266
telemt_connections_me_current 2266
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 161609
telemt_upstream_connect_attempt_total 34086
telemt_upstream_connect_success_total 32377
telemt_upstream_connect_fail_total 1237
telemt_upstream_connect_attempts_per_request{bucket="1"} 33614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8367
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1237
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5645
telemt_me_reconnect_success_total 653
telemt_me_reader_eof_total 401
telemt_me_idle_close_by_peer_total 401
telemt_me_route_drop_no_conn_total 24799282
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8257384
telemt_me_endpoint_quarantine_total 149
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 79
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 79
telemt_me_single_endpoint_shadow_rotate_total 187
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 12469
telemt_desync_full_logged_total 3190
telemt_desync_suppressed_total 9279
telemt_desync_frames_bucket_total{bucket="1_2"} 2163
telemt_desync_frames_bucket_total{bucket="3_10"} 5084
telemt_desync_frames_bucket_total{bucket="gt_10"} 5222
telemt_pool_swap_total 22
telemt_pool_force_close_total 922
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 6270
telemt_me_writer_removed_unexpected_total 563
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5673
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 650
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 272
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5348
telemt_me_writer_teardown_success_total{mode="normal"} 6797
telemt_me_writer_teardown_noop_total 6275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13072
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 30.116163
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13072
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 447
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 8275782
telemt_user_connections_current{user="hello"} 2266
telemt_user_octets_from_client{user="hello"} 50031083034 (46.60 GB)
telemt_user_octets_to_client{user="hello"} 241963031456 (225.35 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 749
telemt_user_unique_ips_recent_window{user="hello"} 368
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 153406.8 (42h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10053069
telemt_connections_bad_total 835633
telemt_connections_current 2057
telemt_connections_me_current 2057
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 220491
telemt_upstream_connect_attempt_total 91769
telemt_upstream_connect_success_total 90827
telemt_upstream_connect_fail_total 808
telemt_upstream_connect_attempts_per_request{bucket="1"} 91635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33380
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 808
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71572
telemt_me_reconnect_success_total 2549
telemt_me_reader_eof_total 2260
telemt_me_idle_close_by_peer_total 2259
telemt_me_route_drop_no_conn_total 5014086
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7939497
telemt_me_endpoint_quarantine_total 1026
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1143
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_me_writers_active_current 86
telemt_desync_total 41022
telemt_desync_full_logged_total 14036
telemt_desync_suppressed_total 26986
telemt_desync_frames_bucket_total{bucket="1_2"} 8327
telemt_desync_frames_bucket_total{bucket="3_10"} 15925
telemt_desync_frames_bucket_total{bucket="gt_10"} 16770
telemt_pool_swap_total 156
telemt_pool_force_close_total 4652
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 570
telemt_me_draining_writers_reap_progress_total 52054
telemt_me_writer_removed_unexpected_total 2306
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5570
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48808
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3997
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 655
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47402
telemt_me_writer_teardown_success_total{mode="normal"} 54378
telemt_me_writer_teardown_noop_total 52055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106433
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.170709
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106433
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 570
telemt_me_refill_failed_total 4258
telemt_me_writer_restored_same_endpoint_total 2146
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 7939763
telemt_user_connections_current{user="hello"} 2057
telemt_user_octets_from_client{user="hello"} 180459200011 (168.07 GB)
telemt_user_octets_to_client{user="hello"} 2983853967353 (2.71 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 877
telemt_user_unique_ips_recent_window{user="hello"} 334
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 90242.9 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10423698
telemt_connections_bad_total 380889
telemt_connections_current 1493
telemt_connections_me_current 1493
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4401433
telemt_upstream_connect_attempt_total 43751
telemt_upstream_connect_success_total 43427
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 43742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18645
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_reconnect_attempts_total 48008
telemt_me_reconnect_success_total 1488
telemt_me_reader_eof_total 1150
telemt_me_idle_close_by_peer_total 1149
telemt_me_route_drop_no_conn_total 3873365
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4997919
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 680
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 27260
telemt_desync_full_logged_total 9194
telemt_desync_suppressed_total 18066
telemt_desync_frames_bucket_total{bucket="1_2"} 5511
telemt_desync_frames_bucket_total{bucket="3_10"} 10775
telemt_desync_frames_bucket_total{bucket="gt_10"} 10974
telemt_pool_swap_total 95
telemt_pool_force_close_total 2956
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 308
telemt_me_draining_writers_reap_progress_total 30946
telemt_me_writer_removed_unexpected_total 1214
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2814
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29375
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2537
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27990
telemt_me_writer_teardown_success_total{mode="normal"} 32189
telemt_me_writer_teardown_noop_total 30953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63142
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.604287
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63142
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 308
telemt_me_refill_failed_total 2704
telemt_me_writer_restored_same_endpoint_total 1323
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4991650
telemt_user_connections_current{user="hello"} 1493
telemt_user_octets_from_client{user="hello"} 107984894644 (100.57 GB)
telemt_user_octets_to_client{user="hello"} 1877602148350 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 570
telemt_user_unique_ips_recent_window{user="hello"} 418
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 71214.0 (19h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 907174
telemt_connections_bad_total 11828
telemt_connections_current 1159
telemt_connections_me_current 1159
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18026
telemt_upstream_connect_attempt_total 35433
telemt_upstream_connect_success_total 35343
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 35417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18754
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 482
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_reconnect_attempts_total 1607
telemt_me_reconnect_success_total 674
telemt_me_reader_eof_total 650
telemt_me_idle_close_by_peer_total 650
telemt_me_route_drop_no_conn_total 310786
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 806289
telemt_me_endpoint_quarantine_total 627
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 592
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 4468
telemt_desync_full_logged_total 1361
telemt_desync_suppressed_total 3107
telemt_desync_frames_bucket_total{bucket="1_2"} 1051
telemt_desync_frames_bucket_total{bucket="3_10"} 1770
telemt_desync_frames_bucket_total{bucket="gt_10"} 1647
telemt_pool_swap_total 76
telemt_pool_force_close_total 1881
telemt_me_writer_close_signal_drop_total 108
telemt_me_draining_writers_reap_progress_total 29211
telemt_me_writer_removed_unexpected_total 629
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2239
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27624
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1803
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27330
telemt_me_writer_teardown_success_total{mode="normal"} 29863
telemt_me_writer_teardown_noop_total 29213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59076
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.335901
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59076
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 108
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 576
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 807395
telemt_user_connections_current{user="hello"} 1159
telemt_user_octets_from_client{user="hello"} 14912542205 (13.89 GB)
telemt_user_octets_to_client{user="hello"} 371708312575 (346.18 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 153411.5 (42h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12344988
telemt_connections_bad_total 1437393
telemt_connections_current 2224
telemt_connections_me_current 2224
telemt_handshake_timeouts_total 337620
telemt_upstream_connect_attempt_total 57401
telemt_upstream_connect_success_total 57175
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 57351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28934
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_reconnect_attempts_total 2256
telemt_me_reconnect_success_total 1199
telemt_me_reader_eof_total 1164
telemt_me_idle_close_by_peer_total 1164
telemt_me_route_drop_no_conn_total 4123112
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9323276
telemt_me_endpoint_quarantine_total 1041
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1146
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
telemt_me_writers_active_current 44
telemt_desync_total 38226
telemt_desync_full_logged_total 12481
telemt_desync_suppressed_total 25745
telemt_desync_frames_bucket_total{bucket="1_2"} 9102
telemt_desync_frames_bucket_total{bucket="3_10"} 14167
telemt_desync_frames_bucket_total{bucket="gt_10"} 14957
telemt_pool_swap_total 170
telemt_pool_force_close_total 4709
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 606
telemt_me_draining_writers_reap_progress_total 51696
telemt_me_writer_removed_unexpected_total 1118
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4255
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48591
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4536
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46987
telemt_me_writer_teardown_success_total{mode="normal"} 52846
telemt_me_writer_teardown_noop_total 51698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104544
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.803369
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104544
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 606
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1049
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9292706
telemt_user_connections_current{user="hello"} 2224
telemt_user_octets_from_client{user="hello"} 179796319760 (167.45 GB)
telemt_user_octets_to_client{user="hello"} 4105327935988 (3.73 TB)
telemt_user_unique_ips_current{user="hello"} 840
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 153407.9 (42h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10688663
telemt_connections_bad_total 1192900
telemt_connections_current 1751
telemt_connections_me_current 1751
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 275643
telemt_upstream_connect_attempt_total 83195
telemt_upstream_connect_success_total 82575
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 83111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34115
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2023
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_reconnect_attempts_total 8802
telemt_me_reconnect_success_total 2021
telemt_me_reader_eof_total 1887
telemt_me_idle_close_by_peer_total 1887
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 5372449
telemt_me_route_drop_channel_closed_total 344
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8259404
telemt_me_endpoint_quarantine_total 1165
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1151
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 37831
telemt_desync_full_logged_total 12207
telemt_desync_suppressed_total 25624
telemt_desync_frames_bucket_total{bucket="1_2"} 9419
telemt_desync_frames_bucket_total{bucket="3_10"} 14113
telemt_desync_frames_bucket_total{bucket="gt_10"} 14299
telemt_pool_swap_total 162
telemt_pool_force_close_total 4556
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 51184
telemt_me_writer_removed_unexpected_total 1912
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5346
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47817
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4117
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46628
telemt_me_writer_teardown_success_total{mode="normal"} 53163
telemt_me_writer_teardown_noop_total 51189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104352
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.160811
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104352
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 1644
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 8265486
telemt_user_connections_current{user="hello"} 1751
telemt_user_octets_from_client{user="hello"} 145274008473 (135.30 GB)
telemt_user_octets_to_client{user="hello"} 3151167805635 (2.87 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 736
telemt_user_unique_ips_recent_window{user="hello"} 233
```
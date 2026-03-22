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

# Server Metrics 2026-03-22 15:23:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 65819.5 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2291394
telemt_connections_bad_total 123748
telemt_connections_current 1669
telemt_connections_me_current 1669
telemt_handshake_timeouts_total 85649
telemt_upstream_connect_attempt_total 24390
telemt_upstream_connect_success_total 24389
telemt_upstream_connect_attempts_per_request{bucket="1"} 24389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1007
telemt_me_reconnect_success_total 415
telemt_me_reader_eof_total 418
telemt_me_idle_close_by_peer_total 418
telemt_me_route_drop_no_conn_total 1850401
telemt_me_route_drop_channel_closed_total 746
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1944092
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 453
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 515
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
telemt_me_writers_active_current 43
telemt_desync_total 9657
telemt_desync_full_logged_total 2981
telemt_desync_suppressed_total 6676
telemt_desync_frames_bucket_total{bucket="1_2"} 2622
telemt_desync_frames_bucket_total{bucket="3_10"} 3622
telemt_desync_frames_bucket_total{bucket="gt_10"} 3413
telemt_pool_swap_total 73
telemt_pool_force_close_total 2217
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 405
telemt_me_draining_writers_reap_progress_total 22246
telemt_me_writer_removed_unexpected_total 405
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1607
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20845
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2170
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20029
telemt_me_writer_teardown_success_total{mode="normal"} 22452
telemt_me_writer_teardown_noop_total 22251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44703
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 194.389392
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44703
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 405
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 366
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1940954
telemt_user_connections_current{user="hello"} 1669
telemt_user_octets_from_client{user="hello"} 29352810000 (27.34 GB)
telemt_user_octets_to_client{user="hello"} 523144892248 (487.22 GB)
telemt_user_unique_ips_current{user="hello"} 654
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 79185.6 (21h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3517320
telemt_connections_bad_total 317024
telemt_connections_current 1133
telemt_connections_me_current 1133
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 84238
telemt_upstream_connect_attempt_total 50020
telemt_upstream_connect_success_total 49418
telemt_upstream_connect_fail_total 530
telemt_upstream_connect_attempts_per_request{bucket="1"} 49948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 530
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5680
telemt_me_reconnect_success_total 1951
telemt_me_reader_eof_total 1878
telemt_me_idle_close_by_peer_total 1878
telemt_me_route_drop_no_conn_total 3507557
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2789923
telemt_me_endpoint_quarantine_total 642
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 612
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
telemt_desync_total 10764
telemt_desync_full_logged_total 5969
telemt_desync_suppressed_total 4795
telemt_desync_frames_bucket_total{bucket="1_2"} 2528
telemt_desync_frames_bucket_total{bucket="3_10"} 4249
telemt_desync_frames_bucket_total{bucket="gt_10"} 3987
telemt_pool_swap_total 75
telemt_pool_force_close_total 2228
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 186
telemt_me_draining_writers_reap_progress_total 31346
telemt_me_writer_removed_unexpected_total 1834
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3626
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29557
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 318
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29118
telemt_me_writer_teardown_success_total{mode="normal"} 33183
telemt_me_writer_teardown_noop_total 31346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64529
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.570313
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64529
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 186
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1661
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 2801282
telemt_user_connections_current{user="hello"} 1133
telemt_user_octets_from_client{user="hello"} 34172163827 (31.83 GB)
telemt_user_octets_to_client{user="hello"} 608844954574 (567.03 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 667
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 154045.5 (42h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15119787
telemt_connections_bad_total 1387307
telemt_connections_current 2430
telemt_connections_me_current 2430
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 366889
telemt_upstream_connect_attempt_total 69949
telemt_upstream_connect_success_total 69854
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 69871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1662
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2582
telemt_me_reconnect_success_total 1331
telemt_me_reader_eof_total 1268
telemt_me_idle_close_by_peer_total 1267
telemt_me_route_drop_no_conn_total 13732043
telemt_me_route_drop_channel_closed_total 134
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12098947
telemt_me_endpoint_quarantine_total 974
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
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
telemt_me_writers_active_current 43
telemt_desync_total 48884
telemt_desync_full_logged_total 15342
telemt_desync_suppressed_total 33542
telemt_desync_frames_bucket_total{bucket="1_2"} 10999
telemt_desync_frames_bucket_total{bucket="3_10"} 19116
telemt_desync_frames_bucket_total{bucket="gt_10"} 18769
telemt_pool_swap_total 166
telemt_pool_force_close_total 5633
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 921
telemt_me_draining_writers_reap_progress_total 50652
telemt_me_writer_removed_unexpected_total 1224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4416
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46765
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5174
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 459
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45019
telemt_me_writer_teardown_success_total{mode="normal"} 51181
telemt_me_writer_teardown_noop_total 50702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101883
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 290.454252
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101883
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 921
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 1142
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 12100440
telemt_user_connections_current{user="hello"} 2430
telemt_user_octets_from_client{user="hello"} 169392180173 (157.76 GB)
telemt_user_octets_to_client{user="hello"} 3107736656595 (2.83 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 1003
telemt_user_unique_ips_recent_window{user="hello"} 298
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 154047.0 (42h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10900986
telemt_connections_bad_total 1050913
telemt_connections_current 1643
telemt_connections_me_current 1643
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 322236
telemt_upstream_connect_attempt_total 82130
telemt_upstream_connect_success_total 80978
telemt_upstream_connect_fail_total 828
telemt_upstream_connect_attempts_per_request{bucket="1"} 81806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32788
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 828
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3889
telemt_me_reconnect_success_total 1566
telemt_me_reader_eof_total 1439
telemt_me_idle_close_by_peer_total 1439
telemt_me_route_drop_no_conn_total 4322652
telemt_me_route_drop_channel_closed_total 477
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8137749
telemt_me_endpoint_quarantine_total 971
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1166
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
telemt_me_writers_active_current 39
telemt_desync_total 36108
telemt_desync_full_logged_total 12126
telemt_desync_suppressed_total 23982
telemt_desync_frames_bucket_total{bucket="1_2"} 8861
telemt_desync_frames_bucket_total{bucket="3_10"} 13894
telemt_desync_frames_bucket_total{bucket="gt_10"} 13353
telemt_pool_swap_total 164
telemt_pool_force_close_total 5069
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 649
telemt_me_draining_writers_reap_progress_total 48950
telemt_me_writer_removed_unexpected_total 1471
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4518
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45760
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4597
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 472
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43881
telemt_me_writer_teardown_success_total{mode="normal"} 50278
telemt_me_writer_teardown_noop_total 48966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99244
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 98.852253
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99244
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 649
telemt_me_refill_failed_total 125
telemt_me_writer_restored_same_endpoint_total 1335
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 8076630
telemt_user_connections_current{user="hello"} 1643
telemt_user_octets_from_client{user="hello"} 202970740937 (189.03 GB)
telemt_user_octets_to_client{user="hello"} 3640793795998 (3.31 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 672
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 154011.2 (42h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10336059
telemt_connections_bad_total 884881
telemt_connections_current 1420
telemt_connections_me_current 1420
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 329795
telemt_upstream_connect_attempt_total 67346
telemt_upstream_connect_success_total 66420
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 66602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31305
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2053
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4618
telemt_me_reconnect_success_total 1858
telemt_me_reader_eof_total 1616
telemt_me_idle_close_by_peer_total 1615
telemt_me_route_drop_no_conn_total 5096470
telemt_me_route_drop_channel_closed_total 353
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7804021
telemt_me_endpoint_quarantine_total 1057
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 1128
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_warm_current 36
telemt_desync_total 35783
telemt_desync_full_logged_total 11860
telemt_desync_suppressed_total 23923
telemt_desync_frames_bucket_total{bucket="1_2"} 9052
telemt_desync_frames_bucket_total{bucket="3_10"} 13667
telemt_desync_frames_bucket_total{bucket="gt_10"} 13064
telemt_pool_swap_total 160
telemt_pool_force_close_total 5021
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 681
telemt_me_draining_writers_reap_progress_total 49377
telemt_me_writer_removed_unexpected_total 1756
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4952
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46093
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4484
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 537
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44356
telemt_me_writer_teardown_success_total{mode="normal"} 51045
telemt_me_writer_teardown_noop_total 49448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100493
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3169.904461
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100493
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 681
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1612
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 7797146
telemt_user_connections_current{user="hello"} 1420
telemt_user_octets_from_client{user="hello"} 180170852729 (167.80 GB)
telemt_user_octets_to_client{user="hello"} 3238077198121 (2.95 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 555
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 24291.1 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9934867
telemt_connections_bad_total 608507
telemt_connections_current 2158
telemt_connections_me_current 2158
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 164584
telemt_upstream_connect_attempt_total 34291
telemt_upstream_connect_success_total 32573
telemt_upstream_connect_fail_total 1237
telemt_upstream_connect_attempts_per_request{bucket="1"} 33810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5284
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1237
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5647
telemt_me_reconnect_success_total 654
telemt_me_reader_eof_total 402
telemt_me_idle_close_by_peer_total 402
telemt_me_route_drop_no_conn_total 24817175
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8283321
telemt_me_endpoint_quarantine_total 149
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 79
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 79
telemt_me_single_endpoint_shadow_rotate_total 189
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
telemt_desync_total 12528
telemt_desync_full_logged_total 3209
telemt_desync_suppressed_total 9319
telemt_desync_frames_bucket_total{bucket="1_2"} 2168
telemt_desync_frames_bucket_total{bucket="3_10"} 5093
telemt_desync_frames_bucket_total{bucket="gt_10"} 5267
telemt_pool_swap_total 22
telemt_pool_force_close_total 922
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 6448
telemt_me_writer_removed_unexpected_total 564
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1132
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5844
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 650
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 272
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5526
telemt_me_writer_teardown_success_total{mode="normal"} 6976
telemt_me_writer_teardown_noop_total 6453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13429
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 30.120319
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13429
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 448
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 8301716
telemt_user_connections_current{user="hello"} 2158
telemt_user_octets_from_client{user="hello"} 52560491350 (48.95 GB)
telemt_user_octets_to_client{user="hello"} 249334235664 (232.21 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 803
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 154017.7 (42h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10076865
telemt_connections_bad_total 838528
telemt_connections_current 1432
telemt_connections_me_current 1432
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 221138
telemt_upstream_connect_attempt_total 92168
telemt_upstream_connect_success_total 91214
telemt_upstream_connect_fail_total 812
telemt_upstream_connect_attempts_per_request{bucket="1"} 92026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1265
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 812
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71583
telemt_me_reconnect_success_total 2559
telemt_me_reader_eof_total 2270
telemt_me_idle_close_by_peer_total 2269
telemt_me_route_drop_no_conn_total 5020969
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7957435
telemt_me_endpoint_quarantine_total 1035
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1144
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
telemt_me_writers_active_current 43
telemt_desync_total 41152
telemt_desync_full_logged_total 14079
telemt_desync_suppressed_total 27073
telemt_desync_frames_bucket_total{bucket="1_2"} 8363
telemt_desync_frames_bucket_total{bucket="3_10"} 15977
telemt_desync_frames_bucket_total{bucket="gt_10"} 16812
telemt_pool_swap_total 157
telemt_pool_force_close_total 4676
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 574
telemt_me_draining_writers_reap_progress_total 52431
telemt_me_writer_removed_unexpected_total 2316
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5594
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49171
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3997
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 679
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47755
telemt_me_writer_teardown_success_total{mode="normal"} 54765
telemt_me_writer_teardown_noop_total 52432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107197
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.296242
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107197
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 574
telemt_me_refill_failed_total 4258
telemt_me_writer_restored_same_endpoint_total 2156
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 7957671
telemt_user_connections_current{user="hello"} 1432
telemt_user_octets_from_client{user="hello"} 180667621951 (168.26 GB)
telemt_user_octets_to_client{user="hello"} 2990683717181 (2.72 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 607
telemt_user_unique_ips_recent_window{user="hello"} 374
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 90853.9 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10461603
telemt_connections_bad_total 383204
telemt_connections_current 1708
telemt_connections_me_current 1708
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4417668
telemt_upstream_connect_attempt_total 43972
telemt_upstream_connect_success_total 43648
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 43963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_reconnect_attempts_total 48013
telemt_me_reconnect_success_total 1493
telemt_me_reader_eof_total 1156
telemt_me_idle_close_by_peer_total 1155
telemt_me_route_drop_no_conn_total 3878946
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5013365
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
telemt_desync_total 27338
telemt_desync_full_logged_total 9224
telemt_desync_suppressed_total 18114
telemt_desync_frames_bucket_total{bucket="1_2"} 5519
telemt_desync_frames_bucket_total{bucket="3_10"} 10815
telemt_desync_frames_bucket_total{bucket="gt_10"} 11004
telemt_pool_swap_total 95
telemt_pool_force_close_total 2956
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 308
telemt_me_draining_writers_reap_progress_total 31133
telemt_me_writer_removed_unexpected_total 1219
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2820
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29562
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2537
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28177
telemt_me_writer_teardown_success_total{mode="normal"} 32382
telemt_me_writer_teardown_noop_total 31140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63522
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.605023
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63522
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 308
telemt_me_refill_failed_total 2704
telemt_me_writer_restored_same_endpoint_total 1328
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5007083
telemt_user_connections_current{user="hello"} 1708
telemt_user_octets_from_client{user="hello"} 108253020972 (100.82 GB)
telemt_user_octets_to_client{user="hello"} 1884394914254 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 673
telemt_user_unique_ips_recent_window{user="hello"} 292
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 71824.7 (19h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 920957
telemt_connections_bad_total 11859
telemt_connections_current 1078
telemt_connections_me_current 1078
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18103
telemt_upstream_connect_attempt_total 35634
telemt_upstream_connect_success_total 35543
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 35617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18876
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 489
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_reconnect_attempts_total 1608
telemt_me_reconnect_success_total 675
telemt_me_reader_eof_total 652
telemt_me_idle_close_by_peer_total 652
telemt_me_route_drop_no_conn_total 315502
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 819466
telemt_me_endpoint_quarantine_total 627
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 598
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
telemt_me_writers_active_current 46
telemt_desync_total 4528
telemt_desync_full_logged_total 1379
telemt_desync_suppressed_total 3149
telemt_desync_frames_bucket_total{bucket="1_2"} 1068
telemt_desync_frames_bucket_total{bucket="3_10"} 1798
telemt_desync_frames_bucket_total{bucket="gt_10"} 1662
telemt_pool_swap_total 76
telemt_pool_force_close_total 1908
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 29431
telemt_me_writer_removed_unexpected_total 630
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2266
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27819
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1830
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27523
telemt_me_writer_teardown_success_total{mode="normal"} 30085
telemt_me_writer_teardown_noop_total 29433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59518
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.464144
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59518
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 577
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 820544
telemt_user_connections_current{user="hello"} 1078
telemt_user_octets_from_client{user="hello"} 15020053497 (13.99 GB)
telemt_user_octets_to_client{user="hello"} 375450727019 (349.67 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 154022.2 (42h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12368156
telemt_connections_bad_total 1438957
telemt_connections_current 2097
telemt_connections_me_current 2097
telemt_handshake_timeouts_total 338533
telemt_upstream_connect_attempt_total 57644
telemt_upstream_connect_success_total 57417
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 57594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_reconnect_attempts_total 2257
telemt_me_reconnect_success_total 1200
telemt_me_reader_eof_total 1165
telemt_me_idle_close_by_peer_total 1165
telemt_me_route_drop_no_conn_total 4129980
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9342175
telemt_me_endpoint_quarantine_total 1045
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1148
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
telemt_me_writers_active_current 43
telemt_desync_total 38285
telemt_desync_full_logged_total 12503
telemt_desync_suppressed_total 25782
telemt_desync_frames_bucket_total{bucket="1_2"} 9111
telemt_desync_frames_bucket_total{bucket="3_10"} 14188
telemt_desync_frames_bucket_total{bucket="gt_10"} 14986
telemt_pool_swap_total 171
telemt_pool_force_close_total 4709
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 606
telemt_me_draining_writers_reap_progress_total 51889
telemt_me_writer_removed_unexpected_total 1119
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4265
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48775
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4536
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47180
telemt_me_writer_teardown_success_total{mode="normal"} 53040
telemt_me_writer_teardown_noop_total 51891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104931
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.806320
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104931
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 606
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1050
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9311582
telemt_user_connections_current{user="hello"} 2097
telemt_user_octets_from_client{user="hello"} 180261227296 (167.88 GB)
telemt_user_octets_to_client{user="hello"} 4114663360428 (3.74 TB)
telemt_user_unique_ips_current{user="hello"} 791
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 154018.8 (42h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10709878
telemt_connections_bad_total 1195859
telemt_connections_current 1708
telemt_connections_me_current 1708
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 276617
telemt_upstream_connect_attempt_total 83466
telemt_upstream_connect_success_total 82842
telemt_upstream_connect_fail_total 540
telemt_upstream_connect_attempts_per_request{bucket="1"} 83382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2026
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 540
telemt_me_reconnect_attempts_total 8807
telemt_me_reconnect_success_total 2025
telemt_me_reader_eof_total 1891
telemt_me_idle_close_by_peer_total 1891
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 5378477
telemt_me_route_drop_channel_closed_total 344
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8275902
telemt_me_endpoint_quarantine_total 1170
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
telemt_me_writers_active_current 43
telemt_desync_total 37913
telemt_desync_full_logged_total 12237
telemt_desync_suppressed_total 25676
telemt_desync_frames_bucket_total{bucket="1_2"} 9441
telemt_desync_frames_bucket_total{bucket="3_10"} 14133
telemt_desync_frames_bucket_total{bucket="gt_10"} 14339
telemt_pool_swap_total 163
telemt_pool_force_close_total 4556
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 51396
telemt_me_writer_removed_unexpected_total 1916
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5357
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48022
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4117
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46840
telemt_me_writer_teardown_success_total{mode="normal"} 53379
telemt_me_writer_teardown_noop_total 51401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104780
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.168457
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104780
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 1648
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 8282022
telemt_user_connections_current{user="hello"} 1708
telemt_user_octets_from_client{user="hello"} 145920301837 (135.90 GB)
telemt_user_octets_to_client{user="hello"} 3158909709051 (2.87 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 674
telemt_user_unique_ips_recent_window{user="hello"} 222
```